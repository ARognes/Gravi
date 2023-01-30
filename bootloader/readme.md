# About
Load the .hex bootloader onto any Gravi board over SWD. Use a Segger JLink, Black Magic Probe, Development Kit, or any other SWD programmer.

# How do I make modifications?
The [Adafruit_nRF52_Bootloader](https://github.com/adafruit/Adafruit_nRF52_Bootloader) repo has instructions on building the code for this hex file. Many hex files will be generated, use the nosd version.

`gravi/` is the board .h files used to decide pin placements and documentation. 
