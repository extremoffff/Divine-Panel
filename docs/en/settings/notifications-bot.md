# Personal Telegram notifications bot

This is a separate feature from the subscription bot, [@divinepanel_bot](https://t.me/divinepanel_bot) — the panel can send sale notifications and respond to commands through **your own** Telegram bot, one you create yourself. Available on the PRO and ULTIMATE plans.

## Setting it up

1. Create a bot through the official [@BotFather](https://t.me/BotFather) on Telegram (the `/newbot` command) and get its token.
2. Find your numeric Telegram chat ID (for example, via a bot like @userinfobot).
3. In the panel, open the settings icon (the gear) in the sidebar → **Notifications**.

**[SCREENSHOT PLACEHOLDER: Notifications window]**

4. Fill in the fields:
   - **Bot token** — your bot's token from BotFather.
   - **Chat ID** — your numeric chat ID.
   - **TG proxy** (optional) — a proxy for the bot in `ip:port:login:password` format, if Telegram is blocked on your network.
5. Click **SAVE**.

The panel starts polling your bot for new messages and commands, responding only to messages from the chat ID you set — messages and commands from anyone else are ignored entirely.

The **UNLINK** button disconnects the bot — notifications and commands stop working until you set it up again.

If your subscription lapses (plan drops below PRO), the bot automatically stops responding to commands, and picks back up as soon as the subscription is restored.

## Automatic notifications

Without any commands, the bot sends you a notification whenever an item sells on market.csgo, Waxpeer, or DMarket:

```
Sold
Account: <name>
Marketplace: <Market.CSGO / Waxpeer / DMarket>
Item: <name>
Amount: <amount> <currency>
Time: <time>
```

The bot also sends a separate message if the panel's license token expires, or if an account has built up a run of network errors on its proxy — a signal to check that account's proxy.

## Commands

Send the bot `/help` (or `/h`) to see the list of commands right in the chat.

### /bal

Shows balances across every account on every marketplace at once (market.csgo, Steam, Waxpeer, DMarket), in each marketplace's own currency, including any frozen/held amount. The list is paginated, with buttons to page through it, and shows a grand total per currency at the top.

**[SCREENSHOT PLACEHOLDER: bot's reply to /bal]**

### /acc

Shows exactly what's currently listed for sale, per account — only on marketplaces enabled for that account. Identical items are grouped together with their average price (e.g. `x3 (avg. $12.50)`). The list is paginated too.

**[SCREENSHOT PLACEHOLDER: bot's reply to /acc]**

### /transfer

Transfers a balance between accounts on market.csgo or Waxpeer — entirely button-driven, no manual amount entry (the entire balance is transferred):

1. Choose a marketplace — Market.CSGO or Waxpeer.
2. Choose a mode — **Between my accounts** (move a balance from one of your accounts to another) or **Collect from all** (consolidate every account's balance into one).
3. Choose the source account (for transfers between your own accounts).
4. Choose the destination — either from your own account list, or tap **Other recipient** and enter an outside recipient's market.csgo API key or Waxpeer SteamID64 manually.
5. Confirm the operation.

**[SCREENSHOT PLACEHOLDER: /transfer dialog in the bot]**

## What's next

To switch the panel's own interface language, see [Interface language](language.md).
