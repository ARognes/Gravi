# Contour Split

This is a 42 or 36 key, bluetooth keyboard with at least 100mAh battery life per side

Idk exactly what to call this keyboard. The main focus of it is to eliminate the extra area where the system on a chip (SoC) is commonly located. However I've gotten carried away and removed much more. 

A minimal amount of tenting will be required to hold the battery underneath.

## Names:
- Estoc
- Crawlerboard
- Gravby
- Gravi
- Grash
- Mash
- Contour Split

## Features:
- Split in 2 halves
- Bluetooth low energy
- nRF52 family
- On-board SMD components
- No center microcontroller area
- Minimal visible space without keys
- Battery underneath tenting towards usb-c edge
- Milmax sockets

There may be 2 sizes for standard and low profile switch types
- Cherry MX / Kailh
- Kailh choc

The main focus is the Kailh choc board (low profile).

Rohs and FCC compliance will be a hurdle.
A case will need to be built, by this time aesthetics will be more of a concern.

# Schematic
![Schematic](Images/V0.3_schematic.png)
![Render](Images/pcb_V0.2.jpg)

# Issues
When plugged in to usb-c, the MS88SF31 module on board gets very hot very quickly, > 85 Celcius don't touch the board hot.

The J-Link SWD interface does not work and I am not able to program the nrf52833.

I think the issue is with the battery and that the MS88SF31 is either getting too much or too little voltage. The Texas Instruments BQ24072 may be at fault here.


# Prototypes
![Prototype](Images/20230113_211543.jpg)

## Revision 3
![Prototype](Images/20230113_211636.jpg)

# Revision 2
(Looks the same as rev 3)

# Revision 1
![Prototype](Images/20220814_204147.jpg)
![Prototype](Images/20220814_204212.jpg)
![Prototype](Images/20220814_204232.jpg)
![Prototype](Images/20220814_204256.jpg)
