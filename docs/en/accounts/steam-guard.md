# Steam Guard: codes and confirmations

Every account card in Account Manager shows a Steam Guard code and a counter of active confirmations — you can work with both right from the panel, without opening the Steam Guard app on your phone.

**[SCREENSHOT PLACEHOLDER: account card with Steam Guard code and confirmation counter]**

## The authenticator code

The five-digit code refreshes automatically every 30 seconds — a progress bar underneath shows the current cycle. The panel calculates the code itself from the loaded maFile, without contacting Steam's servers.

Click the code to copy it to your clipboard — a "Copied" flag appears.

If the code doesn't show, or shows an error, check that the account has a valid maFile loaded (the field from adding/editing an account).

## Confirmations

Next to the code, a counter button shows the number of active Steam confirmations (trade confirmations, listing requests, and so on). An exclamation mark instead of a number means the panel couldn't fetch the list.

Click the counter to open the list of active confirmations:

**[SCREENSHOT PLACEHOLDER: confirmations popup list]**

Each confirmation shows an icon, a title, and a short description; trades additionally show the trading partner (SteamID64, clickable to copy) and item previews. Listings carry a separate "LISTING" badge.

Each row can be confirmed (✓ Accept) or declined (✕ Decline) individually.

## Automatic acceptance

To avoid confirming every action by hand, the panel has automation settings. Click the gear-shaped **Settings** button on the Account Manager toolbar — a settings panel drops down:

**[SCREENSHOT PLACEHOLDER: Steam Guard settings panel]**

- **Auto-accept listings** — automatically accepts confirmations for listing items for sale.
- **Auto-accept gifts (empty trades)** — automatically accepts incoming trades that take nothing from your side (gifts).
- **Poll interval** — how often, in seconds (minimum 5), the panel checks Steam for new confirmations and trades.

Settings apply immediately on change and cover every account.

## What's next

Learn how to configure the marketplaces themselves and price thresholds — see [Account and marketplace settings](account-settings.md).
