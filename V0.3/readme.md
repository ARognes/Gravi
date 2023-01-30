# V0.3 Ordered - 
Uses normal-voltage mode, 3.3V over VDD + VDDH.

# Issues
When plugged in to usb-c, the MS88SF31 module on board gets very hot very quickly, > 85 Celcius don't touch the board hot.

The J-Link SWD interface does not work and I am not able to program the nrf52833.

I think the issue is with the battery and that the MS88SF31 is either getting too much or too little voltage. The Texas Instruments BQ24072 may be at fault here.