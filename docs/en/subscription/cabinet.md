# Cabinet and subscription management

Tap **Cabinet** in the bot's main menu. The screen shows:

- **Balance** — your current USD balance.
- **Subscription** — your plan (PRO/ULTIMATE), or "none" if you don't have one.
- **Expires** — when your subscription ends (or "lifetime"/"—").
- **Next plan** — only shown if you've already bought a different plan in advance, which will kick in once the current one ends.

**[SCREENSHOT PLACEHOLDER: Cabinet screen]**

Cabinet gives access to three sections: **Manage**, **Top Up**, **Subscribe**.

## Managing your subscription

The **Manage** section is only available with an active subscription (PRO or ULTIMATE) — without one, the bot shows a message telling you to get a subscription first.

**[SCREENSHOT PLACEHOLDER: "Subscription management" screen]**

Inside, there are three items:

### Tokens

Shows your main token (used to log into the panel) and, if issued, a separate parser token. A token is a long string you copy and paste into the panel (see [Activating your license](../installation/activate-license.md)).

**[SCREENSHOT PLACEHOLDER: token list screen]**

### Reset HWID

The panel links itself to the hardware (HWID) of the specific computer it's activated on. If you need to move the panel to a different computer, you first need to reset that link here.

1. Tap **Reset HWID**.
2. Confirm the action.
3. The link is removed and all active sessions for the token are ended — the next activation, on any computer, links it fresh.

**[SCREENSHOT PLACEHOLDER: HWID reset confirmation screen]**

### Parser (ULTIMATE only)

If you need to use the Parser and Calculator sections of the panel on a **different device** than the one running the main panel (say, the panel runs on a server while you open Parser from your home PC), you can issue a separate, additional token.

What makes the parser token different:
- It isn't tied to a device HWID — you can use it from several computers at once.
- It only grants access to the Parser and Calculator sections, nothing else.
- It doesn't renew separately — its expiry always matches the main token's.
- It's issued once; you can't issue another if one already exists — the current one is always visible under "Tokens."

Available on the ULTIMATE plan only.

**[SCREENSHOT PLACEHOLDER: parser token issuance screen]**

## What's next

With your token in hand, move on to [Installing the Panel](../installation/download.md) if you haven't installed it yet, or straight to [Activating your license](../installation/activate-license.md).
