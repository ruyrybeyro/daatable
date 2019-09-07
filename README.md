# daatable
Z80 DAA printing table for ZX Spectrum - for visualizing and debugging DAA output.

For cross compiling it and loading in a emulator, a TAP can be created using pasmo. As in:

pasmo  --tapbas daa.asm daa.tap

Then, when it loads it can be run typing:

RANDOMIZE USR 50000
