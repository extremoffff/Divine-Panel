# DMarket overview

The **DMarket** section in the sidebar is a separate marketplace that works differently from market.csgo/Waxpeer: items need to be physically deposited from Steam onto your DMarket balance before they can be sold. Available on the PRO and ULTIMATE plans.

Before starting, an account needs to be prepared for DMarket the same way as for the other marketplaces — see [Account and marketplace settings](../accounts/account-settings.md#preparing-an-account-prepare).

The DMarket page has two tabs: **Inventory manager** and **Price**.

**[SCREENSHOT PLACEHOLDER: DMarket page, Inventory manager tab]**

## Inventory manager — managing your inventory

1. Pick a DMarket-prepared account and a game from the dropdowns at the top of the page.
2. The inventory list has a status filter: **All**, **In Steam** (not yet deposited), **In inventory** (on the DMarket balance, not listed), **On sale** (already listed for sale).
3. Check the items you want (or use **Select all** / **Select none**).

Available actions:

- **Deposit selected** — deposits the selected items from Steam onto DMarket. This is one shared trade request for the whole selected batch, not a separate transfer per item — progress is shown by stage, not by item count.
- **Remove from sale** — unlists an item. This is a required step before withdrawing: DMarket won't let you withdraw an item while it's listed.
- **Withdraw selected** — withdraws the selected items from DMarket back to your Steam inventory.

**[SCREENSHOT PLACEHOLDER: deposit in progress with the progress indicator]**

## Price — thresholds and pricing

The second tab mirrors the P2P Items table, but for DMarket only:

| Column | Meaning |
|---|---|
| Title | Item name |
| Qty | Quantity |
| Market min | The item's lowest current price on DMarket |
| Avg | Average price from recent sales |
| Buy price | Buy price, if set |
| Profit | Estimated profit after DMarket's fees |
| Threshold | The price threshold you set |

Setting thresholds and buy prices works exactly like it does in P2P — see [Price thresholds](../p2p/thresholds.md) and [Buy price and profit calculator](../p2p/buy-price-profit.md). DMarket's background repricing cycle ticks roughly every 20 seconds — the **↻ Refresh** button lets you update the table manually without waiting for the next tick.

**[SCREENSHOT PLACEHOLDER: DMarket Price tab]**

## What's next

For direct trading inside Steam itself (not through a third-party marketplace), see [Steam Manager](../steam-manager/inventories.md).
