[Русский](README.md) | **English**

# PocketOption Signal for Windows — releases

This repository contains **only release builds** of PocketOption Signal for Windows
and the auto-update feed. There is no source code here.

- Download the latest version: [Releases → Latest](https://github.com/pocketoption-signal/windows-releases/releases/latest)
- Each release contains `PocketOptionSignal-Setup-{version}.exe`, `update.json` and `update.json.sig`.
- The app checks `releases/latest` automatically and installs updates only if the
  signature of `update.json` and the SHA-256 of the installer are valid.

Releases are published automatically by CI from the private development repository.
