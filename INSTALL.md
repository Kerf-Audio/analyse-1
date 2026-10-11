# Installing Kerf Audio Analyse 1

Requires REAPER 7.8 or later. **Available now for Windows 10 or 11 (x64) and Linux x86_64 (glibc 2.35+). macOS is coming soon.**

## With ReaPack (recommended)

This is the recommended way to install. You get updates automatically.

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
   On Windows and Linux there's no shortcut to begin with; add one under
   **Actions › Show action list**.

To try fixes before they reach everyone, right-click Analyse 1 in
**Browse packages** and enable **pre-releases** for it.

## Manual install

If you can't use ReaPack:

1. Download the file for your system from [Releases](../../releases):
   - Windows: `reaper_analyser-x64.dll`
   - Linux: `reaper_analyser-x86_64.so`
2. In REAPER, choose **Options > Show REAPER resource path in explorer/finder**.
3. Copy the file into the `UserPlugins` folder there.
4. Restart REAPER.

## Upgrading from an earlier build

If you installed an earlier build of Analyse 1 by hand or with an installer, delete every
`reaper_analyser*` file from `UserPlugins` **before** installing with ReaPack.
Otherwise REAPER may load two copies.

## Uninstalling

- **ReaPack:** Browse packages, right-click Analyse 1, **Uninstall**, Apply, restart REAPER.
- **Manual:** delete the file from `UserPlugins` and restart REAPER.
