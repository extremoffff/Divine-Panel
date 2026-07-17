# Reprice

The **Reprice** tab is a separate mechanism, independent from P2P/DMarket, that automatically recalculates prices for lots already listed for sale on the Steam Community Market. Unlike P2P and DMarket, the panel doesn't auto-list new items here — it only watches items that are already listed and relists them at an updated price.

**[SCREENSHOT PLACEHOLDER: Reprice tab]**

## Its own toolbar

Unlike the other Steam Manager tabs, Reprice has its own toolbar:

- Account picker — here, unlike Inventories/Sell orders/Buy orders, **All accounts** is available, since a threshold applies to an item rather than to one specific account.
- A game and currency switcher.
- A **↻ Refresh** button.
- A **Profit** button — the same automatic-threshold-by-profit-percentage settings used elsewhere, see [Buy price and profit calculator](../p2p/buy-price-profit.md).
- A timer button showing the current repricing interval, letting you change it.

## The table

Columns: **Title**, **Qty**, **Market min**, **My price** (your current Steam listing price), **Buy price**, **Profit**, **Threshold**.

Thresholds and buy prices work exactly like they do in P2P — see [Price thresholds](../p2p/thresholds.md).

## Repricing interval

Click the timer button to change how often the panel rechecks and relists your already-listed Steam lots at an updated price. The default is 24 hours; a shorter interval keeps prices fresher, but also removes and relists lots more often.

**[SCREENSHOT PLACEHOLDER: repricing interval settings window]**

## What's next

For the full overview of every Steam Manager tab, see [Inventories](inventories.md).
