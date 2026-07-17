# Adding a single account

The **Account Manager** section (labeled "Account Manager" in the sidebar) is the only section of the panel available without a subscription. This is where every Steam account the panel works with is added and stored.

**[SCREENSHOT PLACEHOLDER: Account Manager page with the account list]**

The toolbar at the top has **Balances**, **Money Transfer**, **PayPass**, **Settings**, and **Add profile** buttons. To add a new account, click **Add profile**.

## Choosing how to add it

A window opens with two options:

- **Single account** — add one profile by hand.
- **Batch add** — import many accounts at once (see [Batch-adding accounts](batch-add.md)).

**[SCREENSHOT PLACEHOLDER: Single account / Batch add choice window]**

Choose **Single account**.

## Form fields

**[SCREENSHOT PLACEHOLDER: single-account form]**

| Field | Required | Description |
|---|---|---|
| Name | yes | An arbitrary display name — how the account appears inside the panel. Unrelated to the Steam login. |
| Proxy | yes | Proxy in `ip:port:login:password` format. Each account needs its own proxy. |
| Steam username | yes | The Steam account's login. |
| Steam password | yes | The Steam account's password. Hidden behind dots — hold the eye icon to reveal it temporarily. |
| maFile | yes | The Steam Guard mobile authenticator file (`.json`, from SDA or a similar mobile authenticator). Click "Choose" and pick the file on your computer. |
| MarketCSGO Paypass | no | market.csgo's payment password — optional, can be set later too. |
| Comment | no | A free-form note about the account. |

Profile names and Steam logins both have to be unique — the panel won't let you add two accounts with the same name, or the same Steam login under two different names.

Click **Save** — the new profile appears in the list. All marketplaces (market.csgo, Waxpeer, DMarket) start out disabled for a new account — they need to be prepared and enabled separately, see [P2P Marketplaces](../p2p/prepare.md).

## What's next

- To add many accounts at once, see [Batch-adding accounts](batch-add.md).
- For Steam Guard codes and confirmations, see [Steam Guard: codes and confirmations](steam-guard.md).
