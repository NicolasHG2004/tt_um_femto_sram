<!---
This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.
-->

## How it works

FemtoRV32 Quark RISC-V SoC adapted for Sky130 / Tiny Tapeout where the 32x32 register file is implemented using a 1RW OpenRAM SRAM macro (`sky130_sram_32x32`) controlled by a 3-bit single-edge FSM.

## How to test

Connect an SPI Flash with the firmware, reset the chip (`rst_n`), and observe UART TX (`uo[7]`) at 115200 baud (27 MHz clock).

## External hardware

SPI Flash, optional SPI RAM, and USB-UART adapter.
