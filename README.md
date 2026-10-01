# Vortex NV PState and VRAM Clock Locker

Holds an NVIDIA card at a fixed performance state and memory clock.

**Official source:** this repository, and the [Vortex Industries Discord](https://discord.gg/QtyBucygQ6). Anything found elsewhere is not ours and has not been checked.

## Install

1. Open [Releases](../../releases) and download the newest one.
2. Run **`Vortex_PState_Locker.exe`**.

No installer, no dependencies, and no admin unless the tool says it needs it.

## What it does

- Locks P-State so clocks do not drop mid-frame
- Locks the VRAM clock
- NVIDIA only

## Notes

- Portable. Nothing is written outside your user profile.
- The source sits in this repo next to the build.
- Questions and bug reports: the [Discord](https://discord.gg/QtyBucygQ6), in `#help` and `#bug-reports`.

## Disclaimer

This is a system tweak. It changes real Windows settings. Read what it does before running it, and use the tool's own restore option if something behaves unexpectedly. Provided as is, with no warranty.
