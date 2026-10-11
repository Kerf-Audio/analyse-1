# Installing Kerf Audio Analyse 1

Requires REAPER 7.8 or later, on macOS 11+, Windows 10 or 11 (x64), or Linux x86_64.

## With ReaPack (recommended)

This is the way to install on every platform, and the only way on macOS. You get
updates automatically.

1. Install [ReaPack](https://reapack.com) if you don't have it.
2. In REAPER, open **Extensions > ReaPack > Import repositories...**
3. Paste this URL and click OK:
   ```
   https://raw.githubusercontent.com/Kerf-Audio/reapack/main/index.xml
   ```
   If you already added it for Kerf Modulators, skip this step.
4. Open **Extensions > ReaPack > Browse packages**, search for **Analyse 1**,
   right-click it and choose **Install**, then click **Apply**.
5. Restart REAPER.
6. Open the panel from **Extensions > Kerf Audio Analyse 1: Show/hide panel**
   (default shortcut Option+V on macOS).

To try fixes before they reach everyone, right-click Analyse 1 in
**Browse packages** and enable **pre-releases** for it.

## Manual install (Windows and Linux only)

On macOS, install with ReaPack. On Windows or Linux, if you can't use ReaPack:

1. Download the file for your system from [Releases](../../releases):
   - Windows: `reaper_analyser-x64.dll`
   - Linux: `reaper_analyser-x86_64.so`
2. In REAPER, choose **Options > Show REAPER resource path in explorer/finder**.
3. Copy the file into the `UserPlugins` folder there.
4. Restart REAPER.

## Upgrading from an earlier build

If you installed an earlier build of Analyse 1 by hand or with the old macOS installer, delete every
`reaper_analyser*` file from `UserPlugins` **before** installing with ReaPack.
Otherwise REAPER may load two copies.

## Uninstalling

- **ReaPack:** Browse packages, right-click Analyse 1, **Uninstall**, Apply, restart REAPER.
- **Manual (Windows and Linux):** delete the file from `UserPlugins` and restart REAPER.
