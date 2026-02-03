<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This Verilog design implements a 4-bit synchronous up-counter with
reset and enable control signals.

## How to test

Initialize the clock, reset, and enable signals. First assert the reset
and then de-assert the reset. Then start counting by setting the enable
= 1. Stop counting by setting enable = 0. After counting ends, end the
simulation. See the testbench for more details.

## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any

NONE
## Pinout
### Inputs
| Pin | Name |
|---------|------|
| ui[0] | enable |
| ui[1] | |
| ui[2] | |
| ui[3] | |
| ui[4] | |
| ui[5] | |
| ui[6] | |
| ui[7] | |
### Outputs
| Pin | Name |
|---------|------|
| uo[0] | counter_out[0] |
| uo[1] | counter_out[1] |
| uo[2] | counter_out[2] |
| uo[3] | counter_out[3] |
| uo[4] | |
| uo[5] | |
| uo[6] | |
| uo[7] | |
