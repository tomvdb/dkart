# dkart

An open-hardware and software Gameboy flash-cart and hardware peripheral framework

## hardware

The hardware consists of an ATMEGA328 chip & a couple TI i2c port-expanders, and a microSD card.

## firmware

The firmware runs on the ATMEGA328 to emulate ROM/RAM reading/writing data to a microSD card formatted FAT32.

## software

A menu runs on the Gameboy to choose the current ROM/RAM. I wrote it using GBDK, on a Mac.

To compile, run

    make

in the software directory. Make sure you have GBDK, and edit Makefile to have the correct path to GBDK & RGBDS.