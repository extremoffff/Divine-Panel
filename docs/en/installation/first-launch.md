# First launch

## Extracting

Extract the `DivinePanel-Setup-win64.zip` archive into any folder on your computer (your desktop, or `C:\DivinePanel`, for example). Inside you'll find **`Launcher.exe`** and a handful of accompanying folders/files — leave them alone, everything needs to stay together in the same place.

**[SCREENSHOT PLACEHOLDER: contents of the extracted folder]**

## Launching

Always start the panel **through `Launcher.exe`** — never through files inside the nested folders. Launcher is what checks for a newer panel version on every launch and pulls it in automatically if needed — you never have to update the panel itself by hand.

On first launch (and every launch after), `Launcher.exe` shows a small window with an animated logo and a progress indicator while it checks for updates — usually a matter of seconds. The panel itself then opens automatically in your browser.

**[SCREENSHOT PLACEHOLDER: Launcher window with progress bar]**

**[SCREENSHOT PLACEHOLDER: the panel open in a browser]**

## The tray icon

After launch, the panel keeps running in the background — an icon appears in the Windows system tray (next to the clock). Closing the browser tab does not shut the panel down; it keeps running so repricing and notifications aren't interrupted.

To reopen the panel, click the tray icon and choose **Open panel**. To fully close the program, choose **Exit** from the same tray menu.

**[SCREENSHOT PLACEHOLDER: tray icon menu]**

## Only one instance runs at a time

If you launch `Launcher.exe` again while the panel is already running, it simply opens the already-running panel in your browser instead of starting a second copy.

## Requirements

The panel is a Windows application. You don't need to install .NET or anything else separately — everything required is already bundled in the downloaded archive.

## What's next

On first launch, the panel will ask for a token — see [Activating your license](activate-license.md).
