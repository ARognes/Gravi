# Parts List

Much of this is outdated, just check the BOM

All possible parts to select for the BOM

---


---

## Resistors
|       Name        | In Stock |  QTY   | Price  | Resistance |                                                  Datasheet                                                   |                                                                                Company |
| :---------------: | :------: | :----: | :----: | :--------: | :----------------------------------------------------------------------------------------------------------: | -------------------------------------------------------------------------------------: |
|  RC0402FR-0710KP  | 174,000  | 1,000  | $6.52  |   10 kΩ    |    [DS](https://www.yageo.com/upload/media/product/productsearch/datasheet/rchip/PYu-RC_51_RoHS_P_2.pdf)     |      [YAGEO](https://www.digikey.com/en/products/detail/yageo/RC0402FR-0710KP/4935264) |
|  RC0402FR-072KP   | 110,000  | 1,000  | $6.52  |    2 kΩ    |    [DS](https://www.yageo.com/upload/media/product/productsearch/datasheet/rchip/PYu-RC_51_RoHS_P_2.pdf)     |       [YAGEO](https://www.digikey.com/en/products/detail/yageo/RC0402FR-072KP/4935276) |
| CR0402-16W-5101FT |   Many   | 10,000 | $15.40 |   5.1 kΩ   |                    [DS](https://page.venkel.com/hubfs/Resources/Datasheets/CR-Series.pdf)                    | [Venkel](https://www.digikey.com/en/products/detail/venkel/CR0402-16W-5101FT/12327266) |
|  RC0402FR-7W1KL   |  6,000   | 1,000  | $4.51  |    1 kΩ    | [DS](https://www.yageo.com/upload/media/product/productsearch/datasheet/rchip/PYu-RC_Group_51_RoHS_L_11.pdf) |      [YAGEO](https://www.digikey.com/en/products/detail/yageo/RC0402FR-7W1KL/12698822) |

1005 Metric

Possibly need 1k resistor

Venkel has free shipping

---

## Crystals NOT NEEDED WITH MINEW M33

|         Name         |  Size mm  |  QTY  | In Stock |  Price  |                                        Datasheet                                         |                                                    Distributor                                                     |
| :------------------: | :-------: | :---: | :------: | :-----: | :--------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------: |
| FC-12M 32.7680KA-AC3 | 2.05x1.25 |  250  |  51,000  | $277.20 |       [DS](https://support.epson.biz/td/api/doc_check.php?dl=brief_FC-12D&lang=en)       |              [Digikey](https://www.digikey.com/en/products/detail/epson/FC-12M-32.7680KA-AC3/5259892)              |
|      CM8V-T1A..      |  2.0x1.2  | 1,000 |  83,000  | $350.24 | [DS](https://www.microcrystal.com/fileadmin/Media/Products/32kHz/Datasheet/CM8V-T1A.pdf) | [Digikey](https://www.digikey.com/en/products/detail/micro-crystal-ag/CM8V-T1A-32.768KHZ-9PF-20PPM-TA-QC/10500166) |

---

## Power / Charging Chip

|    Name     |  QTY  | In Stock |   Price   |                                                         Datasheet                                                          |                                         Distributor                                         |
| :---------: | :---: | :------: | :-------: | :------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------: |
| BQ24075RGTR | 1,000 |  12,000  | $2,876.69 |                 [DS](https://pdf.utmel.com/r/datasheets/texasinstruments-bq24075rgtr-datasheets-3513.pdf)                  |      [Utmel](https://www.utmel.com/productdetail/texasinstruments-bq24075rgtr-9878457)      |
| BQ24076RGTT | 1,000 |   736    | $1,697.50 | [DS](https://www.ti.com/general/docs/suppproductinfo.tsp?distId=10&gotoUrl=https%3A%2F%2Fwww.ti.com%2Flit%2Fgpn%2Fbq24076) | [Digikey](https://www.digikey.com/en/products/detail/texas-instruments/BQ24076RGTT/7915907) |
| BQ24076GTR  | 1,000 |  3,623   | $1,414.00 | [DS](https://www.ti.com/general/docs/suppproductinfo.tsp?distId=10&gotoUrl=https%3A%2F%2Fwww.ti.com%2Flit%2Fgpn%2Fbq24076) | [Digikey](https://www.digikey.com/en/products/detail/texas-instruments/BQ24076RGTR/8105808) |
| BQ24076RGTR | 1,000 | 235,397  |   $808    |                                 [DS](https://www.ti.com/document-viewer/BQ24076/datasheet)                                 |          [Texas Instruments](https://www.ti.com/product/BQ24076?login-check=true)           |
| BQ24072RGTR | 1,000 | 136,747  |   $808    |                                          [DS](https://www.ti.com/lit/gpn/BQ24072)                                          |      [Texas Instruments](https://www.ti.com/product/BQ24072/part-details/BQ24072RGTR)       |

BQ24072 should be used as it has battery charge voltage min & max of 4.2 V,
exactly what a 3.7 V battery needs.

Switch and Pulse chargers also exist but 


XC6220B331MR-G is a voltage regulator.
It outputs 3.3 V minimum, 1 A current
Input max 6 V

---

## JST Battery Connector

|  End   |            Name            | In Stock |  QTY  |  Price  |                                             Datasheet                                             |                                                 Distributor                                                  |
| :----: | :------------------------: | :------: | :---: | :-----: | :-----------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------: |
| Female | BM02B-ACHSS-GAN-TF(LF)(SN) | 422,000  | 1,000 | $287.44 | [DS](https://media.digikey.com/pdf/Data%20Sheets/JST%20PDFs/ACH_1.2Pitch_DisconnectableCrimp.pdf) | [Digikey](https://www.digikey.com/en/products/detail/jst-sales-america-inc/BM02B-ACHSS-GAN-TF-LF-SN/1647788) |
|  Male  |         ACHR-02V-S         |  43,550  | 1,000 | $73.43  |                      [DS](https://www.jst-mfg.com/product/pdf/eng/eACH.pdf)                       |        [Digikey](https://www.digikey.com/en/products/detail/jst-sales-america-inc/ACHR-02V-S/1647783)        |

---

## USB-C

|    Name    | In Stock |  QTY  |  Price  |                                       Datasheet                                       |                                                   Distributor                                                   |
| :--------: | :------: | :---: | :-----: | :-----------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------: |
| 2169900003 |  5,110   | 1,000 | $723.24 |                                                                                       |                                                                                                                 |
<!-- | 2169900001 |  5,110   | 1,000 | $723.24 | [DS](https://www.molex.com/webdocs/datasheets/pdf/en-us/2169900001_IO_CONNECTORS.pdf) | [Digikey](https://www.digikey.com/en/products/detail/molex/2169900001/13913743?s=N4IgTCBcDa4IwDYCcSAM7VxAXQL5A) | -->

---

## USB-C ESD Protection
|    Name    | In Stock |  QTY  |  Price  |                                       Datasheet                                       |                                                   Distributor                                                   |
| :--------: | :------: | :---: | :-----: | :-----------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------: |
| RCLAMP7522T.TNT | 8,821 | 1,000 | $495 | [DS](https://semtech.my.salesforce.com/sfc/p/E0000000JelG/a/2R000000HTqQ/iEJdTMWfTgfi7KiSi1OQ6ZvqU_A4rcQHQVQUbS4fs.w?__hstc=212684107.36d9ad8a12d3eb2fd96795c09692ad6d.1632523249633.1632523249633.1645563373098.2&__hssc=212684107.4.1645563373098&__hsfp=2341104755) | [Mouser](https://www.mouser.com/ProductDetail/Semtech/RCLAMP7522TTNT?qs=rBWM4%252BvDhIeZa4mcPs8DUA%3D%3D&utm_source=netcomponents&utm_medium=aggregator&utm_campaign=RCLAMP7522T.TNT&utm_content=Semtech) |
| IP4234CZ6,125 | 21,000 | 1,000 | $158.20 | [DS](https://assets.nexperia.com/documents/data-sheet/IP4234CZ6.pdf) | [Digikey](https://www.digikey.com/en/products/detail/IP4234CZ6,125/1727-4717-2-ND/2296236?utm_campaign=buynow&utm_medium=aggregator&curr=usd&utm_source=octopart) |

---

## LED

|     Name      | Color | In Stock |  QTY  | Price  |                                           Datasheet                                            |                                          Distributor                                           |
| :-----------: | :---: | :------: | :---: | :----: | :--------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------: |
| SML-D12U1WT86 |  Red  |  6,000   | 1,000 | $39.86 | [DS](https://fscdn.rohm.com/en/products/databook/datasheet/opto/led/chip_mono/sml-d12x1-e.pdf) | [Digikey](https://www.digikey.com/en/products/detail/rohm-semiconductor/SML-D12U1WT86/5843853) |
| SML-D12U1WT86 | Green |  6,000   | 1,000 | $39.86 | [DS](https://fscdn.rohm.com/en/products/databook/datasheet/opto/led/chip_mono/sml-d12x1-e.pdf) | [Digikey](https://www.digikey.com/en/products/detail/rohm-semiconductor/SML-D12M1WT86/5843856) |

---

## Mill Max Socket

| 7305-0-15-15-47-27-10-0 | 230,813 | 50,000 | $7,250 | (DS)[https://www.mouser.com/datasheet/2/273/MMMC_S_A0005142907_1-2558040.pdf] | (Mouser)[https://www.mouser.com/ProductDetail/Mill-Max/7305-0-15-15-47-27-10-0?qs=QVz7UnnaAAGZJgZDI7Hd%2FA%3D%3D]
| 3305-0-15-80-47-27-10-0 | 60,000  | 50,000 | $8,200 | (DS)[https://www.mouser.com/datasheet/2/273/mill_max_02192021_3305_0_15_80_47_27_10_0-2036622.pdf] | (Mouser)[https://www.mouser.com/ProductDetail/Mill-Max/3305-0-15-80-47-27-10-0?qs=CiayqK2gdcJ0UcFbwoRx4A%3D%3D]

---
## Switch


## Reset Button


# Alternate Power / Charging Circuit DON't DO THIS

Gotta beat $808 / 1,000

TP4054ST25K | 2,500 | $125 | [LCSC](https://www.lcsc.com/product-detail/PMIC-Battery-Management_TPOWER-TP4054ST25P_C382138.html)
Mosfet
Schottky Diode
