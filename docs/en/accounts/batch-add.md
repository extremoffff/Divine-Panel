# Batch-adding accounts

If you need to add many accounts at once, filling out the single-account form one at a time isn't the way — use batch add instead.

Click **Add profile** → **Batch add**.

**[SCREENSHOT PLACEHOLDER: batch add window with instructions]**

## Preparing the files

Before clicking the add button, prepare three things next to the panel's folder in advance:

1. **`config/logpass.txt`** — one account per line, in the format:
   ```
   login:password
   ```
2. **`config/proxy.txt`** — one proxy per line, in the format:
   ```
   ip:port:login:password
   ```
   The number of lines and their order must **exactly match** `logpass.txt` — the first proxy goes to the first account, the second to the second, and so on.
3. A **`maFile`** folder (next to the panel, not nested under `config`) — place each account's authenticator file inside it, named **exactly like that account's Steam login** (case doesn't matter, any file extension works). For example, an account with the login `login123` needs a file named `login123.maFile`.

## Running the import

Once all three are in place, click **ADD** in the batch add window.

The panel checks logins, proxies, and maFile files line by line and shows import progress with a line-by-line log: green for accounts added successfully, red for lines with an error (login already exists, no matching maFile found, mismatched line counts between the files, and so on).

**[SCREENSHOT PLACEHOLDER: batch import progress with the line-by-line log]**

When it's done, a summary shows how many accounts were added successfully and how many lines failed.

## Important

Batch add never deletes or overwrites anything — it only reads `logpass.txt`/`proxy.txt`/the `maFile` folder and adds new profiles the exact same way manual adding does. Accounts you already added earlier are unaffected, even if their logins are still present in these files.

## What's next

After adding your accounts, set up Steam Guard codes and confirmations — see [Steam Guard: codes and confirmations](steam-guard.md).
