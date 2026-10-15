# Card Studio — Download

ID card design, database and printing software for Windows, macOS and Linux.
No account needed, works offline, and your data stays on your own computer.

## ⬇ Download
Click the link for your computer. These links always give the latest version.

| Computer | Download |
|---|---|
| Windows 10/11 | [Card-Studio-win-x64.exe](https://github.com/equserteam/card-studio-releases/releases/latest/download/Card-Studio-win-x64.exe) |
| Mac with Apple chip (M1/M2/M3/M4) | [Card-Studio-mac-arm64.dmg](https://github.com/equserteam/card-studio-releases/releases/latest/download/Card-Studio-mac-arm64.dmg) |
| Mac with Intel chip | [Card-Studio-mac-x64.dmg](https://github.com/equserteam/card-studio-releases/releases/latest/download/Card-Studio-mac-x64.dmg) |
| Ubuntu / Debian | [Card-Studio-linux-amd64.deb](https://github.com/equserteam/card-studio-releases/releases/latest/download/Card-Studio-linux-amd64.deb) |
| Linux (any) | [Card-Studio-linux-x86_64.AppImage](https://github.com/equserteam/card-studio-releases/releases/latest/download/Card-Studio-linux-x86_64.AppImage) |

Not sure which Mac you have? Apple menu → **About This Mac**: "Apple M…" means Apple chip, "Intel" means Intel.

## Install
**Windows:** Run the `.exe`. If you see "Windows protected your PC", click **More info → Run anyway**.

**Mac:** Open the `.dmg` and drag **Card Studio** to **Applications**, then open it. The app isn't notarized by Apple yet,
so the first time macOS says it "can't be verified":
1. Click **Done**, then open **System Settings → Privacy & Security**.
2. Scroll down to *"Card Studio" was blocked* and click **Open Anyway**. Confirm with your password.

Shortcut: paste this into Terminal once: `xattr -cr "/Applications/Card Studio.app"`

**Linux (Ubuntu/Debian, recommended):** install the `.deb`: `sudo apt install ./Card-Studio-linux-amd64.deb`. Then open **Card Studio**
from the app menu.

**Linux (other distros) — AppImage:** `chmod +x Card-Studio-linux-x86_64.AppImage`, then run it. If nothing happens:
- `libfuse2` is missing: `sudo apt install libfuse2` (it's called `libfuse2t64` on Ubuntu 24.04).
- On Ubuntu 23.10 and newer, start it with `./Card-Studio-linux-x86_64.AppImage --no-sandbox` (the system blocks Chromium's sandbox for AppImages).

## Your data
Everything is saved on your computer and kept when you update or reinstall. In the app, **File → Open data folder** shows the folder;
copy it to back up your data or to move it to another computer.
