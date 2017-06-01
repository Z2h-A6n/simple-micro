# Simple Micro
KiCad files for a simple microcontroller breakout board. Nearly a clone of the
[Sparkfun Pro Micro](https://www.sparkfun.com/products/12640)

## Overview
This is a simple breakout board for the Atmel ATMega32u4 microcontroller that is
very closely based on the Pro Micro by Sparkfun Electonics. The primary
differences between the Pro Micro and the Simple Micro are:
- The Pro Micro is physically smaller.
- The Simple Micro breaks out a few more of the I/O pins on the ATMega.
- The USB pins on the Simple Micro are broken out to through-hole pads as well as a surface-mount USB receptacle.
- The Simple Micro is cheaper (as of this writing).
  - e.g. Making 3 Simple Micros with boards from OSH Park and components from DigiKey cost $34. See the [example parts list](parts-list.txt).
- The Pro Micro comes pre-built.
- The Pro Micro was made by people who presumably know what they are doing, while the Simple Micro was designed by someone with no formal training in microcontroller use or PCB design.

## Files in this repo
Most of the files in the repo are KiCad project files. The other files are:
- assembly.pdf
  - A pdf showing the exposed pads on the bare PCB marked up with component labels to help with assembling the board.
- README.md
  - This document.
