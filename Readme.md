# A2Pico2 Reference Hardware

This repository is the home of the A2Pico2 reference hardware based on the RP2354B processor. Please refer to the repository at https://github.com/oliverschmidt/a2pico2 for general information on A2Pico2.

## Hardware Revision History

Version 1.0 is the innitial design with a 74LVC07 inverting OC driver for some of the A2 lines. However it is obsolete as it is unnecessary to invert the lines or use an OC driver, due to the RP2350 being capable to directly drive OC lines by keeping high impedance state and driving the lines as output "0" only when assetrion is needed.

Version 1.1 is the current version.

The GPIO usage is as follows:

| GPIO    | Usage     |
|:--------|:----------|
| 0       |  UART TX  |
| 1       |  UART RX  |
| 2 - 17  | A0 - A15  |
| 18      | R/W       |
| 19      | PHI0      |
| 20      | M2SEL     |
| 21      | DEVSEL    |
| 22      | IOSEL     |
| 23      | IOSTB     |
| 24      | DMA_IN    |
| 25      | DMA_OUT   |
| 26      | DMA       |
| 27      | INH       |
| 28      | RDY       |
| 29      | NMI       |
| 30      | IRQ       |
| 31      | RESET     |
| 32 - 39 | D0 - D7   |
| 40      | LED       |
| 41      | CLK       |
| 42      | CMD       |
| 43      | DAT0      |
| 44      | DAT1      |
| 45      | DAT2      |
| 46      | DAT3      |
| 47      | Detect    |



