<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

3 XOR, 3 AND and 1 OR gate are connected to the inputs w1,w0,x1,x0.
A input toggle is used to set the gates to high and low, and the outputs are c, s1, s0

## How to test

Set the inputs and check the outputs with the expected results:

| W1 W0 Z1 Z0 | output S1 | output S0 | output C |
|-------------|-----------|-----------|----------|
| 0  0  0  0  |     0     |     0     |    0     |
| 0  0  0  1  |     0     |     1     |    0     |
| 0  0  1  0  |     1     |     0     |    0     |
| 0  0  1  1  |     1     |     1     |    0     |
| 0  1  0  0  |     0     |     1     |    0     |
| 0  1  0  1  |     1     |     0     |    0     |
| 0  1  1  0  |     1     |     1     |    0     |
| 0  1  1  1  |     0     |     0     |    1     |
| 1  0  0  0  |     1     |     0     |    0     |
| 1  0  0  1  |     1     |     1     |    0     |
| 1  0  1  0  |     0     |     0     |    1     |
| 1  0  1  1  |     0     |     1     |    1     |
| 1  1  0  0  |     1     |     1     |    0     |
| 1  1  0  1  |     0     |     0     |    1     |
| 1  1  1  0  |     0     |     1     |    1     |
| 1  1  1  1  |     1     |     0     |    1     |

## External hardware

7 wokwi-led
1 wokwi-dip-switch-8
