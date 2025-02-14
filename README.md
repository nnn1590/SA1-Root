```
  _____             __   _____             _   
 / ____|  /\       /_ | |  __ \           | |  
| (___   /  \ ______| | | |__) |___   ___ | |_ 
 \___ \ / /\ \______| | |  _  // _ \ / _ \| __|
 ____) / ____ \     | | | | \ \ (_) | (_) | |_ 
|_____/_/    \_\    |_| |_|  \_\___/ \___/ \__|
    Version 1.0              by Vitor Vilela
```

SA-1 Root is the base pack of patches for activating and using SA-1
on many different games. SA-1 Root currently has patches for the
following games:

* [Gradius III](Gradius-III) v1.4
* Super Mario World ([SA-1 Pack only](https://github.com/VitorVilela7/SA1-Pack))

What is it?
===========

SA-1 is a co-processor used on some special SNES games, made to work together
with the Super NES CPU and enhance its processing speed, graphics and memory.

With its base 10.74 MHz clock, the SA-1 CPU is four times faster than the
normal SNES CPU processing. The SA-1 CPU and SNES CPU also runs
simultaneously, which can result in five times faster processing over game with
a standard cart setup. With that much power, the Super Accelerator System (SAS)
can be used to process game engines much faster than the normal, allowing more
sprites to be processed at once, more in-game effects, faster loading and much
more.

SA-1 Root not just activates the co-processor, but also modifies a good part of
the game engine to use and explore the chip features, which gives an extreme
boost to the overall performance of the game.

## System Features
* 16-bit 65c816 processor clocked at 10.74 MHz.
* 2 kB fast internal work memory (I-RAM), clocked at 10.74 MHz.
* Multi-processor processing, with parallel operating mode and memory sharing
control.
* Large capacity memory, with a total capability of 8 MB of ROM clocked at
10.74 MHz and 256 kB of BW-RAM, clocked at 5.37 MHz.
* High speed arithmetic hardware of multiplication, division and cumulative
sum.
* Bitmap and Character Conversion functions for fast graphics manipulation.
* Custom DMA circuit for fast transfers between ROM, I-RAM and BW-RAM.
* Variable-Length Bit data processing for enhanced algorithms such as graphics
and data compression.
* Super MMC memory mapping capabilities for BW-RAM and bank switching for
multiple ROM image access and mirroring.

## Differences with SA-1 Pack

SA-1 Root is intended to be the base pack for enabling SA-1 on the games
and optimizing it. SA-1 Pack is intended to be a full featured pack that
not just enables SA-1 and accelerate the game, but also improve the game
engine and provide additonal tools for ROM hacking.

For example, Super Mario World's SA-1 Pack doubles the maximum physical
amount of allowed enemies on screen and includes different shared
routines for additional SA-1 features.

Compatibility
=============

SA-1 Root is warranted to work with real hardware, including SA-1 carts
plus the most up-to-date SNES emulators including bsnes and Snes9x.

ZSNES is not compatible with the SA-1 Root patches.

Credits
=======

SA-1 Root wouldn't be that awesome without help from these people:

* indcsion (additional testing)
* Vitor Vilela (crazy author that did most of the patches)
* You (for using it :D)

Useful Links
============

#### Technical documents

Useful documents for understanding SA-1:

* SNES Dev. Book: https://www.romhacking.net/docs/226/
* SA-1 Registers: https://wiki.superfamicom.org/sa-1-registers
* SA-1 Doc: https://github.com/VitorVilela7/SNES-SA-1-doc/

#### Personal

You can contact make though the following links:

* My Github profile: https://github.com/VitorVilela7
* My Twitter profile: https://twitter.com/HackerVilela
