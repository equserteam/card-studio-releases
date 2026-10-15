# Card Studio — Download

ID card design, database and printing software for Windows, macOS and Linux.
No account needed, works offline, and your data stays on your own computer.

## ⬇ Download
Open **[Releases → Latest](../../releases/latest)** and download the file for your computer:

| Computer | File |
|---|---|
| Windows 10/11 | `Card-Studio-x.y.z-win-x64.exe` |
| Mac with Apple chip (M1/M2/M3/M4) | `Card-Studio-x.y.z-mac-arm64.dmg` |
| Mac with Intel chip | `Card-Studio-x.y.z-mac-x64.dmg` |
| Linux (any) | `Card-Studio-x.y.z-linux-x86_64.AppImage` |
| Ubuntu / Debian | `Card-Studio-x.y.z-linux-amd64.deb` |

## Install
**Windows:** Run the `.exe`. If you see "Windows protected your PC", click **More info → Run anyway**.

**Mac:** Open the `.dmg` and drag **Card Studio** to **Applications**, then open it. The app isn't notarized by Apple yet,
so the first time macOS says it "can't be verified":
1. Click **Done**, then open **System Settings → Privacy & Security**.
2. Scroll down to *"Card Studio" was blocked* and click **Open Anyway**. Confirm with your password.

Shortcut: paste this into Terminal once: `xattr -cr "/Applications/Card Studio.app"`

**Linux:** For the AppImage, right-click → Properties → allow executing, then double-click it. Or install the `.deb`
(`sudo apt install ./Card-Studio-*.deb`).

## Your data
Everything is saved on your computer and kept when you update or reinstall. In the app, **File → Open data folder** shows the folder;
copy it to back up your data or to move it to another computer.
