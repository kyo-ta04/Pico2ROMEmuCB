# Pico2ROMEmu - RP2350B Core Board Version
![Pico2ROMEmu RP2350B Core Board](./IMG/Pico2ROMEmuPCB_CoreBoard_img_2.jpg)
This project is a simple and fast ROM emulator using Pico2ROMEmu with RP2350B Core Board.  
[日本語のReadme](./README.md)
## Features
- For more information, please see [Pico2ROMEmu](https://github.com/kyo-ta04/Pico2ROMEmuBR)

## Structure
- ROM data such as 'saki80mon041_const.c' comes from [saki80mon041.hex](https://github.com/yyhayami/saki80mon041).
UNIMON for SAKI80 is based on the Universal Monitor released by asano, with significant extensions by Aki.H and EMUZ80_Monitor Rev.B04 released for the EMUZ80, and was ported by @yyhayami to run on the Super AKI-80.
- The WeAct Studio RP2350B Core Board is a compact development board equipped with the Raspberry Pi RP2350B microcontroller, measuring just 41.4×41.1mm, yet exposing all 48 I/O pins through two 30-pin headers.  
Github : [WeActStudio.RP2350BCoreBoard](https://github.com/WeActStudio/WeActStudio.RP2350BCoreBoard)

## Schematics and Documents
- ![Pico2ROMEmuCB_sch](./IMG/Pico2ROMEmuCB_sch_2.jpg)
The above is an image of the schematic.
- ![Pico2ROMEmuBR_RUN_img_2](./IMG/Pico2ROMEmuCB_RUN_img_2.jpg)
The above is an example image of execution when using saki80mon041.hex.
- ![Pico2ROMEmuBR_RUN_img_1](./IMG/Pico2ROMEmuCB_RUN_img_1.jpg)
The above is an example image of execution when using SAKI80MB.HEX.


## License
- The source code of this project is under the MIT license.
- For the ROM data part, please refer to the licenses of the original site and the modified source.

## Disclaimer
This software is provided as is. The author is not responsible for any damage.

## Acknowledgments
- @yyhayami（[saki80mon041  creator）](https://github.com/yyhayami/saki80mon041)）
- @electrelic(asano)（[Universal Monitor creator）](https://electrelic.com/electrelic/node/1317)）
- @akih_san(Aki.h)（[EMUZ80-MON creator](https://github.com/akih-san/EMUZ80-MON)）
- Thank you to everyone who gave me advice, liked my posts, and recommended my work on x.com and elsewhere.
- Raspberry Pi Pico SDK developers
- Everyone involved in this project
- Please also check out [Pico2ROMEmu](https://github.com/kyo-ta04/Pico2ROMEmuBR).

---

MIT License

Copyright (c) 2025 kyo-ta04(DragonballEZ)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
