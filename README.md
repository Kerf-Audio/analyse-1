# Kerf Audio Analyse 1

**Free beta.** A docked metering and analysis panel for REAPER.

Loudness, level, stereo image and frequency content in one strip that sits in
REAPER's docker. Show only the modules you need, arrange them how you like, and
pop any of them out into its own window.

A thank-you to the REAPER community, which has inspired me since 2007.

## Status: beta

Analyse 1 has been through extensive code review and works on macOS, Windows
and Linux. It's a beta because it hasn't yet been widely used in real-world
projects, so please report anything that doesn't look right, especially a
reading that disagrees with a meter you trust.

Runs on:
- macOS 11+ (Apple Silicon and Intel)
- Windows 10 and 11 (x64)
- Linux (x86_64)

Please [report bugs](../../issues/new/choose) and ask questions in
[Discussions](../../discussions). Support is through GitHub only. I read every
report and fix what I can, as time allows, but there's no guaranteed timescale.

## Modules

- **LUFS**: momentary (400 ms) and short-term (3 s) loudness, ITU-R BS.1770-4 K-weighting
- **VU**: 300 ms analogue-style dial, 0 VU at −18 dBFS
- **Peak**: fast peak with RMS underlay; dBFS, K-12, K-14 or K-20 scales
- **Goniometer**: L/R vector scope with a phase-correlation bar
- **Scope**: oscilloscope with zero-crossing trigger and zoom
- **Spectrum**: FFT analyser, 20 Hz to 20 kHz on a log scale
- **Spectrogram**: scrolling waterfall
- **Performance**: CPU, output latency and device sample rate
- **Brand**: the Kerf Audio mark with the exact version and build date

## Features

- Show, hide, reorder and resize modules
- Save and recall named layouts
- Pop any module out into its own resizable window
- Freeze any module, or every module at the same instant
- Four accent colours, including one that follows your REAPER theme, in light or dark
- Monitoring tools on the listening path only: Mono, LF solo and Dim
- Master FX bypass, to compare with and without your master processing
- Hover readouts of frequency, note and level on the spectrum and spectrogram
- No plugin to insert; switch analysis off and it uses no processor time

## Roadmap: testing first

This first release phase is for testing and bug fixing. No new features will be
added until version 1.0 is out and stable. Feature requests are welcome in
[Discussions](../../discussions) or as an Issue, and they will be looked at
after 1.0.

## Install

Install with ReaPack. See [INSTALL.md](INSTALL.md) or the [install guide (PDF)](docs/kerf-analyse-1-install-guide.pdf).

## Documentation

- [Install guide (PDF)](docs/kerf-analyse-1-install-guide.pdf)
- [User manual (PDF)](docs/kerf-analyse-1-manual.pdf)

## Licence

Analyse 1 is free to use, including for commercial work, under the
[Kerf Audio Freeware Licence](LICENSE.txt). It is not open source.
Third-party components are listed in [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt).

Danny Wincott, trading as Kerf Audio
