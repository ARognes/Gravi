# Estoc


## Notes

Can ship lithium batteries internationally

Pay for the quick attach battery sockets
MC on bottom, battery inner center
Tent to contain larger battery


### nRF52810
This is a scaled down version of the nRF52832, which has been used in Adafruits and other BlueMicro firmware
Cheap $1.50 - $2.80
Bluetooth LE 5.2
Using GPIO for keys directly, diodes would be unnecessarry


[Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)


### [Ergogen](https://docs.ergogen.xyz/pcbs)

### [Zypher](https://docs.zephyrproject.org/latest/boards/arm/nrf52dk_nrf52810/doc/index.html)
### [ZMK](https://github.com/zmkfirmware/zmk)

### [Architeuthis Dux](https://github.com/tapioki/cephalopoda/tree/main/Architeuthis%20dux)
Very interesting pcb


## TODO
Find a way to put the nRF5810/32 - 33/40 on a pcb and properly control it


## PCB On board Microcontroller
Can use a pcb antenna, which takes more space
or a chip antenna, which is a tiny smb component. May cost more
Check FCC authorizations for 'intentional radiators'
Class B (consumer)

[PCB design guidelines for nRF52---](https://devzone.nordicsemi.com/guides/short-range-guides/b/hardware-and-layout/posts/general-pcb-design-guidelines-for-nrf52)

[AliExpress fully functional chip (too big)](https://es.aliexpress.com/item/3256803082251892.html?_randl_currency=USD&_randl_shipto=US&src=google&aff_fcid=09bf2d07f595417fafba458338e8161e-1651976998586-03536-UneMJZVf&aff_fsk=UneMJZVf&aff_platform=aaf&sk=UneMJZVf&aff_trace_key=09bf2d07f595417fafba458338e8161e-1651976998586-03536-UneMJZVf&terminal_id=92823948a5de40e383b26d53f92c6cbb&afSmartRedirect=y&gatewayAdapt=4itemAdapt)
[nRF52840 FCC CE RoHS $8.82](https://es.aliexpress.com/item/1005001658876997.html?_randl_currency=USD&_randl_shipto=US&src=google&aff_fcid=f2ac1f2a46aa496da2896b598c81a52c-1651982845150-09432-UneMJZVf&aff_fsk=UneMJZVf&aff_platform=aaf&sk=UneMJZVf&aff_trace_key=f2ac1f2a46aa496da2896b598c81a52c-1651982845150-09432-UneMJZVf&terminal_id=92823948a5de40e383b26d53f92c6cbb&afSmartRedirect=y)
[MS88SF31-48](https://www.minew.com/product/nrf52840-ms88sf31/)
- $7.49
- GPIO: 48
- 18.5 x 12.5 x 2
- 85 in stock

[MS50SFB2-32](https://www.minewstore.com/product/nrf52832-ms50sfb-2/)
- $6
- GPIO: 32
- 20 x 12 x 2 mm
- JLCPCB, $3.2278, 850 min order

[MS50SFB2-10](https://www.minewstore.com/product/nrf52810-ms50sfb-2/)
- $5
- GPIO: 32
- 20 x 12 x 2 mm


Production:

[MS88SF31 nRF52833](https://www.minew.com/product/nrf52833-ms88sf31/) $7, 2500 in stock is the main selling point
Shipped from China so $40 shipping fee
42 GPIO
Requires SMT for the connections!



TYPE-C-31-M-12 $0.1469 1000+, 16 pin





## Battery
1000mAh is a good cuttoff point before diminishing returns
20% main will be wasted
70% peripheral will be wasted

If main alternation is available, this may be better aleviated

Anything >= 600mAh works really

(mm)
YOK Energy: 
  YE602663C  6.2  26.3  63.5 

[LiPol Battery](https://www.lipo-battery.com/r)
LP602760: 60	27	6 
LP602660: 60	26	6 
LP602560: 60	25	6 
LP603443: 43  34  6

Ask for JST connectors attached!

Currently, just solder battery straight on


## Battery Charger IC

Texas Instruments

BQ24075 idk which sub-version
GTT is cheaper $0.87

Schematic same as nice!nano



## Small components per side

Resistor 10k ohm x 2
Resistor 2k ohm
Resistor 5.1k ohm x 2

Capacitor 4.7uF x 2
Capacitor 1uF

Charging LED Red/Orange
