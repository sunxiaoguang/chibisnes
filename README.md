# ChibiSNES <!-- omit in toc -->

ChibiSNES is SNES emulator written by Go. This is my favorite hobby project!

Based on [LakeSNES](https://github.com/elzo-d/LakeSnes). It also has some bug fixes.

- [Spec](#spec)
- [Key binding](#key-binding)
  - [Documents](#documents)
- [Credit](#credit)

## Spec

- [X] CPU
- [X] PPU
- [X] SPC700 & DSP
- [X] Controller
- [X] Cartridge
  - [X] LoROM
  - [X] HiROM
  - [X] Read `.srm` data (only 0x2000)
- [ ] Enhancement chip (ToDO)
  - [ ] SuperFX
  - [ ] CX4
  - [ ] DSP-X (DSP-1, DSP-2, DSP-3, DSP-4)
  - [ ] Sharp LR35902
  - [ ] MX15001TFC
  - [ ] OBC-1
  - [ ] Rockwell RC2324DPL
  - [ ] S-DD1
  - [ ] S-RTC
  - [ ] SA1
  - [ ] SPC7110
  - [ ] ST (ST010, ST011, ST018)
- [ ] Encoding system
  - [X] NTSC
  - [ ] PAL


## Key binding

Player 1

|SNES|Key|
|---|---|
| UP, DOWN, LEFT, RIGHT | Arrow Keys |
| Start | Enter |
| Select | Right Shift |
| A | Z |
| B | X |
| Y | C |
| X | V |
| L | A |
| R | F |

### Documents

- [SNES Development Wiki | Super Famicom Development Wiki](https://wiki.superfamicom.org/)
- [Fullsnes - Nocash SNES Specs](https://problemkaputt.de/fullsnes.htm)
- [SnesLab](https://sneslab.net/wiki/Main_Page)
- [q00.snes introduction – [ emudev ]](https://emudev.de/q00-snes/introduction/)
- [elzo-d/LakeSnes: A SNES emulator, in C](https://github.com/elzo-d/LakeSnes)
- [pokemium/snes-docs-ja: WIP: SNES、スーファミ(SFC)の日本語リファレンスです](https://github.com/pokemium/snes-docs-ja)

## Credit

- Font
  - [itouhiro/PixelMplus](https://github.com/itouhiro/PixelMplus)
