# Overview of the Items table

The **P2P Marketplaces** section (in the sidebar) opens the panel's main table — **Items** — showing every item across your accounts that's listed, or ready to be listed, on market.csgo and Waxpeer. Available on the PRO and ULTIMATE plans.

**[SCREENSHOT PLACEHOLDER: main Items table]**

## Toolbar

- **Trade status** — indicator for active trades/item hand-offs.
- **Profit** — opens the automatic threshold settings, see [Buy price and profit calculator](buy-price-profit.md).
- **Game switcher** (CS2/game icon) — market.csgo (with its per-game domains) and Waxpeer both run all four games at once in the background; this switcher only changes what's displayed in the table, not what's actually being repriced.
- **Show only for account** — filters the table to a single account (default is "All accounts," showing items from every account at once).
- Profile/row counter — how many accounts and how many item rows are currently in the table.

## Tabs and search

- **Tradeable** — items ready to sell right now (not Steam-trade-locked).
- **Trade locked** — items Steam doesn't yet allow you to transfer (the usual trade lock after receiving an item).
- The search field filters the table by item name.

## Table columns

| Column | Meaning |
|---|---|
| Item / profiles | The item's name and which accounts hold it |
| Qty | How many units of this item you have |
| Market min | This item's lowest current price on the marketplace |
| Avg | Average price from recent sales |
| Buy price | Your buy price for the item, if set |
| Profit | Estimated profit/loss at the current price, after marketplace fees |
| Threshold | The price threshold you set — the floor (and, if set, ceiling) price the panel won't list the item outside of |

## How the panel decides what to list and at what price

The panel regularly (every few dozen seconds) recalculates the current price for every item on every enabled marketplace, and either lists it for the first time or relists an already-listed item at a new price — within whatever threshold you've set. If no threshold is set for an item in a given currency, it simply won't be listed in that currency.

## What's next

- Before items show up in this table for a given marketplace, the account needs to be prepared for it — see [Preparing an account for a marketplace](prepare.md).
- To set price thresholds, see [Price thresholds](thresholds.md).
