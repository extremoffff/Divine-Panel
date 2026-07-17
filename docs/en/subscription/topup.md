# Topping up your balance

In the bot's main menu, tap **Top Up**. A list of available methods opens:

**[SCREENSHOT PLACEHOLDER: list of top-up methods]**

- **USDT, USDC (EVM)** — BEP-20 (BSC), Arbitrum, and Polygon networks. All three share the same address — they're all EVM-compatible.
- **USDT (TON)**
- **USDT (Aptos)**
- **USDT, USDC (Solana)**
- **Bybit UID** — an internal Bybit transfer by UID (not by network).
- **CryptoBot +3%** — pay with any asset inside the Telegram bot @CryptoBot; CryptoBot's own 3% fee is added on top of the amount credited.

## Topping up with crypto (EVM / TON / Aptos / Solana)

Pick the method you want — the bot shows your personal deposit address:

**[SCREENSHOT PLACEHOLDER: deposit address screen, e.g. EVM]**

1. Send a transfer to the address shown, on one of the supported networks.
2. Wait for network confirmations — your balance is usually credited automatically within a few minutes.
3. The page watches for the deposit for a limited time (usually around 20 minutes). If your transfer arrives later, just open the top-up section for that method again to restart tracking.

The address is permanently tied to your account in the bot and doesn't change — you can top it up as many times as you like.

## Topping up via Bybit UID

1. Tap **Bybit UID** in the list of methods.
2. If you haven't linked a Bybit UID yet, tap **Set Bybit UID** and send it as a message (a number, found in the Bybit app under Profile → UID).
3. Once linked, the bot shows Divine Panel's receiving UID — send USDT via an **internal transfer by UID** (not over the blockchain/network).
4. Your balance is credited automatically within a few minutes of the transfer.

You can change the linked UID any time with the **Change UID** button.

**[SCREENSHOT PLACEHOLDER: Bybit UID top-up screen]**

## Topping up via CryptoBot

1. Tap **CryptoBot +3%**.
2. Send a message with the USD amount that should end up on your balance (e.g. `10` or `10.5`). The amount must be between 1 and 100000.
3. The bot creates an invoice inside @CryptoBot — the amount you'll actually pay is a bit higher than what you typed, since CryptoBot's 3% fee is added on top.
4. Tap **Pay** — CryptoBot opens, where you can pay with any asset it supports (USDT, TON, BTC, ETH, and others) at CryptoBot's own exchange rate.
5. Your balance is credited automatically after payment.

**[SCREENSHOT PLACEHOLDER: CryptoBot invoice screen]**

## What's next

Once your balance is topped up, move on to [Subscribing](subscribe.md).
