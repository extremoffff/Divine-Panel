# Price thresholds

A threshold is the price the panel will never list an item below. Without a threshold set, an item simply won't be auto-listed in that currency.

## Opening the threshold window

In the Items table (or the equivalent tables in DMarket/Steam Manager Reprice), click the **Threshold** cell for the item's row — a window opens to configure that item's threshold.

**[SCREENSHOT PLACEHOLDER: "Set threshold" window]**

## Minimum threshold

The threshold is set separately **for each currency** — USD, RUB, EUR:

- **Min USD threshold**
- **Min RUB threshold**
- **Min EUR threshold**

The same threshold for a given currency applies **to every marketplace enabled for that account at once** — there's no such thing as a separate threshold for market.csgo and a separate one for Waxpeer for the same item; the threshold is shared.

If a currency's field is left empty, the item simply won't be listed in that currency (it can still be listed in other currencies that do have a threshold set).

Even if your threshold is set lower, each marketplace enforces its own minimum price and won't list below it:

- market.csgo: $0.005 / €0.005 / ₽0.5
- Waxpeer: $0.005

## Maximum threshold (optional)

The **Also cap this item with a max threshold** checkbox reveals additional upper-bound fields — **Max USD/RUB/EUR threshold**. If set, the panel won't list the item above this price, even if the market price is higher.

**[SCREENSHOT PLACEHOLDER: expanded max threshold fields]**

## Clearing thresholds

The **Clear thresholds** button in this same window removes every threshold set for the item — both minimum and maximum — across all currencies at once.

## Setting thresholds automatically

You don't have to set a threshold by hand for every single item — if items already have a buy price set, the panel can calculate thresholds automatically based on your target profit. See [Buy price and profit calculator](buy-price-profit.md).

## What's next

To see actual estimated profit rather than just price for each item, set a buy price — see [Buy price and profit calculator](buy-price-profit.md).
