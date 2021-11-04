# (DEPRECATED).tokuya's Linux VST Plugins Collection

Collection of self-compiled Linux VST plugins that I used in my music production. These plugins were built on a VM running Ubuntu 18.04.

**DEPRECATED NOTE: I'm no longer maintaining this repo. CHOWTapeModel has Debian package on ChowDSP website, M8BP2 and Bitrot suite have fairly simple build process that you can do it your own, and the rest are outdated or difficult to build on recent distros.**

## List:
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

## License
Most plugins in this repo are licensed under GPL-3 and/or compatible license.
