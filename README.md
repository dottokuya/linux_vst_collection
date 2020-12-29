# .tokuya's Linux VST Plugins Collection

Collection of self-compiled Linux VST plugins that I used in my music production.

**This repo contains only Linux binaries of said plugins. They usually have pre-built Windows and Mac binaries at their own repos.**

## Current list:
- [ToneZ](https://www.retornz.com/plugins/tonez) by Retornz
- [SuperSpeard](https://github.com/lkjbdsp/lkjb-plugins/tree/master/SuperSpread) by lkjb
- [Bitrot Plugins Suite](https://github.com/grejppi/bitrot) by grejppi
- [StereoKnob](https://github.com/sharki13/stereoknob) by sharki13
- [Magical8bitPlug2](https://github.com/yokemura/Magical8bitPlug2) by yokemura
- [CHOW Tape Model](https://github.com/jatinchowdhury18/AnalogTapeModel) by ChowDSP
- [CTAGDRC](https://github.com/p-hlp/CTAGDRC) by p-hlp

## Installation
- Clone/download this repository
- (optional) Copy to your VST/VST3 folder
    * VST2 (single `.so` file): `~/.vst` or `/usr/lib/vst` (required sudo)
    * VST3 (folder ends with `.vst3` suffix): `~/.vst3` or `/usr/lib/vst3` (required sudo)
- Alternatively, you can set custom path in your DAW to scan all the plugins in the folder without copying (tested on Reaper for Linux)

## Updating
Run `git pull` at repo's directory or manually check this repo from time to time and simply redownload

## Issue/Bug report
I'd suggest open an issue/bug report on plugins repo/forum first, as developers does keep their eye on Linux and will help you debugging and resolve problem. Otherwise, if you think your problem is platform specific, feel free to open an issue here and I'll try to figure out

## License
Most plugins in this repo are licensed under GPL-3 and/or compatible license.
