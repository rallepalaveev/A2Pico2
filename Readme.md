# A2Pico2 Reference Hardware

This repository is the home of the A2Pico2 reference hardware based on the RP2354B processor. It is an expansion mass storage card for Apple2 computers. It can use uSD card or a USB stick for storage. Please refer to the repository at https://github.com/oliverschmidt/a2pico2 for general information on A2Pico2.

## Hardware Revision History

Version 1.0 is the initial design with a 74LVC07 inverting OC driver for some of the A2 lines. However it is obsolete as it is unnecessary to invert the lines or use an OC driver, due to the RP2350 being capable to directly drive OC lines by keeping high impedance state and driving the lines as output "0" only when assertion is needed.

Version 1.1 is also obsolete.

Version 1.2 is current.




