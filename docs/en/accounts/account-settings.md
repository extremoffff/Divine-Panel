# Account and marketplace settings

Each account card in Account Manager has a block for each of three marketplaces — **market.csgo**, **Waxpeer**, and **DMarket**. Every block has a toggle for that account on that marketplace, plus **Prepare**, **Recreate**, and **Copy key** buttons.

**[SCREENSHOT PLACEHOLDER: marketplace block on an account card with the toggle and buttons]**

## Preparing an account (Prepare)

A marketplace toggle can't be turned on until the account has been prepared for it — trying to anyway shows a window explaining that **Prepare** needs to run first.

Click **Prepare** on the marketplace you want — the button shows a spinner while preparation runs:

- **market.csgo** — the panel registers the account on the marketplace itself (if it isn't registered yet), links the trade URL, and issues an API key. Nothing manual is needed from you.
- **Waxpeer** — the panel signs into Steam through an isolated browser profile for this account, authenticates on waxpeer.com via Steam, links the trade URL, and grabs the API key from the site's security settings page.
- **DMarket** — same idea, but DMarket sometimes asks for email confirmation during registration — in that case the panel shows a separate window to enter your email/confirmation link.

Once preparation succeeds, the marketplace toggle becomes available.

**[SCREENSHOT PLACEHOLDER: "Not ready yet" window when trying to enable an unprepared marketplace]**

## Preparing everything at once (Mass Prepare)

If you need to prepare all three marketplaces for an account, there's a button that runs Prepare on each not-yet-prepared marketplace in sequence. If everything's already prepared, the button is disabled.

## Reissuing a key (Recreate)

The **Recreate** button repeats preparation but reissues the API key: the old key is invalidated immediately. For DMarket and Waxpeer, the panel shows an additional warning about the consequences (invalidating the old key can affect already-active listings) that you need to confirm.

## Enabling a marketplace

Once a marketplace is prepared, its toggle turns on automatic listing and repricing for that account's items on that marketplace. For how the panel decides what to list and at what price, see [P2P Marketplaces](../p2p/overview.md) and [DMarket](../dmarket/overview.md).

## Copying the key

The **Copy key** button copies the marketplace's current active API key to your clipboard.

## market.csgo currency

The market.csgo block has its own currency switcher button (RUB/USD/EUR). Changing it requires confirmation — the panel asks whether you really want to switch the account's currency from the current one to the one you picked.

**[SCREENSHOT PLACEHOLDER: market.csgo currency picker]**

## What's next

For editing or deleting an already-added account, see [Editing and deleting](edit-delete.md). For setting price thresholds on items, see [Price thresholds](../p2p/thresholds.md).
