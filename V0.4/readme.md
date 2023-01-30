# V0.4 - Ordered Jan 30, 2023
After much testing and debugging of the previous two versions, it was decided that working with an nrf52840 would be easier. This is because the .hex bootloader could be pre-programmed by Minew. The bootloader has UF2 capabilities so the keyboard could simply be programmed over USB and no SWD would be required.

# Changes
- nrf52840 instead of nrf52833
- corrected resistor pad sizes from 0603 to 0402
- pre-install bootloader before soldering
- specify soldering max temp during assembly

