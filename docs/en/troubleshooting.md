# FAQ & troubleshooting

## The panel won't start / won't open in a browser

Make sure you're launching `Launcher.exe` specifically, not another file inside the extracted folder. If the panel was already running (its icon still sitting in the tray), launching `Launcher.exe` again just opens the already-running panel in your browser — that's expected behavior, not an error.

If the browser doesn't open on its own, open `panel.html` in the panel's folder by hand, or go to the address printed when it launches.

## The panel is running, but I don't see a window or icon

After launch, the panel minimizes into the Windows system tray (next to the clock) and keeps running in the background. Closing the browser tab doesn't shut it down. To fully close the program, find the tray icon and choose **Exit**.

## The token won't activate

- Make sure the token was copied in full, with no extra spaces.
- If it says the token is already linked to another account/computer, it was activated on a different device before. Reset the link in the bot: [Cabinet → Manage → Reset HWID](subscription/cabinet.md#reset-hwid).
- Check that your subscription is active and hasn't expired — status and expiry are shown in the bot's [Cabinet](subscription/cabinet.md).

## A marketplace toggle won't turn on

The account hasn't been prepared for that marketplace yet. Click **Prepare** on the account's card in Account Manager first — see [Account and marketplace settings](accounts/account-settings.md).

## An item isn't getting listed for sale

Check whether a threshold is set for that item in the currency the marketplace trades in. Without a threshold in a given currency, the panel won't list the item in that currency — see [Price thresholds](p2p/thresholds.md).

## The proxy indicator is red

This means the account has racked up a run of failed network requests through its proxy — the account is temporarily excluded from the Tradeable table until the proxy starts working again. Check that account's proxy (in the profile edit form) — it may have stopped working or changed IP.

If the account has a personal Telegram notifications bot configured (see [Personal Telegram notifications bot](settings/notifications-bot.md)), a separate message will arrive there for this error.

## A section is unavailable and shows a subscription window

The feature needs a higher plan than the one currently active. The window links to divinepanel.com (to see the plans) and to [@divinepanel_bot](https://t.me/divinepanel_bot) (to buy or upgrade) — see also [Plans](README.md#plans).

## I need to move the panel to a different computer

1. In the bot: [Cabinet → Manage → Reset HWID](subscription/cabinet.md#reset-hwid).
2. Install the panel on the new computer (see [Downloading](installation/download.md)).
3. Activate the same token again — see [Activating your license](installation/activate-license.md).

## Where to go if this didn't solve it

The **Support** button in the main menu of the Telegram bot [@divinepanel_bot](https://t.me/divinepanel_bot) — a direct line to support.
