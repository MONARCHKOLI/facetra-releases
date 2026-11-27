# Facetra downloads

Facetra is a fast, private business intelligence app for your desktop.
Your data stays on your computer.

**[Download the latest version](../../releases/latest)**

| System | File |
|---|---|
| Windows 10/11 | `Facetra-<version>-win-….exe` |
| macOS (Apple Silicon) | `Facetra-<version>-mac-arm64.dmg` |
| macOS (Intel) | `Facetra-<version>-mac-x64.dmg` |
| Ubuntu / Debian | `Facetra-<version>-linux-amd64.deb` (or `arm64`) |
| Other Linux | `Facetra-<version>-linux-x86_64.AppImage` |

Facetra checks this page for new versions and offers to update.

## First start

These installers aren't code-signed yet, so your system asks once:

- **Windows:** if "Windows protected your PC" appears, choose
  **More info → Run anyway**.
- **macOS:** right-click Facetra in Applications and choose **Open**. If
  macOS says the app "is damaged", run this once in Terminal:
  `xattr -cr /Applications/Facetra.app`
- **Ubuntu:** install the `.deb` with `sudo apt install ./Facetra-*.deb`.
  The AppImage works too, but starts with a warning on Ubuntu 24.04 (Help
  in the app explains it).

The source code is not public. This repository only builds and hosts the
installers.
