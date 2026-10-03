# pid-spoon-electrical

## Purpose

Electrical work for PID Spoon: schematics, PCB, power, and sensor hardware.

Shared interfaces and decisions: see pid-spoon-interfaces.

## Scope

In this repo: schematics, PCB sources and released fab packages, power and sensor documentation, reviewed test summaries.

Not in this repo: firmware (pid-spoon-controls), CAD and drawings (pid-spoon-mechanical), vendor datasheet PDFs and raw test data (Drive).

## Owner

Team lead: @luislopezrondon. Org team: `pid-spoon-electrical`.

## Folder map

| Path | Holds |
| --- | --- |
| `schematics/` | TODO: fill at kickoff |
| `pcb/` | TODO: fill at kickoff |
| `power/` | TODO: fill at kickoff |
| `sensors/` | TODO: fill at kickoff |
| `docs/` | Reviewed notes, test summaries |

The folder map is provisional. It follows the structure used by the matching EXO repo.

## How to contribute

1. Pull `main` before you start: `git pull origin main`.
2. Branch: `git checkout -b <your-name>/<short-description>`.
3. Commit in small steps with a message that says what changed.
4. Push: `git push -u origin <branch>`.
5. Open a pull request and fill in all four sections of the template.
6. One teammate reviews and approves, then you merge. Nobody pushes to `main` directly.

## What never goes here

- Passwords, tokens, API keys, personal email addresses, phone numbers. This repo is public. Deleting a file does not remove it from history; a committed secret must be rotated.
- On-body sensor data, and any data from a person wearing part of a device. Gate S2 is open. Nothing of that kind goes into this repo or into Drive until a written faculty or PI determination exists.
- Native CAD binaries and raw bench logs. Those stay in Drive. Commit a summary, not the raw file.

## Drive folder

[Electrical](https://drive.google.com/drive/folders/16DcGIMgwtcuZrYI7QaQJs6lVmQ6q1_ZE)

Raw files stay in Drive. A short summary goes in `docs/` and names the Drive file and the date. If the link says you need access, use Request access or ask a Project Lead.

## Board

PID Spoon organization board: to be added once the board is created.

## Related repos

- https://github.com/IEEE-USF-EXO/pid-spoon-controls
- https://github.com/IEEE-USF-EXO/pid-spoon-mechanical
