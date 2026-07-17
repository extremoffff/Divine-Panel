# Parser overview

The **Parser** section compares prices and stock between two marketplaces you pick, side by side — handy for spotting opportunities to buy cheaper on one marketplace and sell higher on another. Available on the ULTIMATE plan only (or with a separate parser token — see [Cabinet → Parser](../subscription/cabinet.md#parser-ultimate-only)).

**[SCREENSHOT PLACEHOLDER: Parser page with two marketplaces selected]**

## Choosing a game and marketplaces

At the top of the page:

- A game switcher — **CS2, Dota 2, Rust, TF2**.
- **Platform 1** and **Platform 2** — two dropdowns listing dozens of supported marketplaces (Steam, market.csgo, Waxpeer, DMarket, CSFloat, Skinport, Buff.Market, LIS-Skins, and many more — the exact set depends on the selected game).
- A ⇄ button between them — quickly swap the two platforms.
- A currency switcher (USD by default).
- A currency-icon button — exchange rates: automatic (live) or entered manually.

## Filters

Each of the two platforms has its own filter panel (collapsible), plus a separate global filters panel:

**Per-platform filters:**
- Price from / to
- Minimum quantity (Qty ≥)
- Float from / to (a wear/quality indicator, not available on every marketplace)
- Maximum ban days (Ban days ≤)
- StatTrak / Souvenir / Normal / Stickers-only toggles

**Global filters:**
- Minimum/maximum profit percentage (Profit %)
- Hide items overstocked on platform 2
- Minimum sales over the last 7 days — separately for Steam and for platform 2

**[SCREENSHOT PLACEHOLDER: expanded filter panels]**

All filters apply to the results table immediately — there's no separate "Apply" step.

## Auto-refresh

The auto-refresh checkbox and the interval field next to it (in seconds, minimum 15) turn on periodic automatic updates to the table without manually clicking **Refresh**.

## Search and refresh

The search field filters the table by item name. The **↻ Refresh** button fetches fresh data on demand.

## What's next

To estimate the profit of a trade between two marketplaces before actually making the purchase, use the [Profit calculator](../tools/calculator.md).
