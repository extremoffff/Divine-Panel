# Buy price and profit calculator

## Buy price

For the **Profit** column in the table to show real profit rather than just the current price, the panel needs to know what the item originally cost you.

Click the buy price cell for an item — the **Set buy price** window opens with a field for each currency: **Buy price USD**, **Buy price RUB**, **Buy price EUR**.

**[SCREENSHOT PLACEHOLDER: Set buy price window]**

The buy price you set is combined with that specific marketplace's fees (sale + withdrawal) to compute your final profit:

- market.csgo: 5% + 5%
- Waxpeer: 6% + 1%

## Automatic thresholds by target profit percentage

Instead of setting a threshold by hand for every item, you can ask the panel to calculate them all at once — based on your target profit percentage — for every item that already has a buy price set.

Click the **Profit** button on the Items table toolbar (or the equivalent one on the DMarket/Steam Manager pages) → the **Automatic thresholds** window opens.

**[SCREENSHOT PLACEHOLDER: Automatic thresholds window]**

1. Enter a **Target net profit/loss %** — your target profit percentage after marketplace fees. For example, `10` means +10% profit; you can also enter a negative value, like `-15`, if you're willing to sell at up to a 15% loss.
2. Check which accounts to apply the calculation to (**Select all** / **Select none** buttons and the account list).
3. Click **APPLY**.

This is a one-time action: the panel calculates and saves a new Min threshold once for every eligible item (with a buy price set) on the selected accounts — overwriting the existing threshold. It doesn't keep recalculating afterward if the buy price changes — run it again manually if you need to.

## The floating profit calculator

Separate from the table, there's a **floating calculator** — a small window you can drag anywhere on screen, which stays open while you switch between pages in the panel. See [Profit calculator](../tools/calculator.md).

## What's next

For the full picture of Account Manager and the marketplaces, see [Overview of the Items table](overview.md). For DMarket, see [DMarket overview](../dmarket/overview.md).
