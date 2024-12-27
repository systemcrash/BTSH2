# BT Smart Hub 2 (BTSH2) (old style?)
- Manufacturer: Arcadyan ( MAC 8C:83:94: * : * : * )
- 1 x DSL port (RJ45 4p)
- 1 x POTS (6p BS 6312)
- 4 x Gbit (RJ45 8p, 1 x WAN, 3 x LAN in "Fibre" mode)
- 1 x USB
- 1 x 12VDC 1.5A


* Info sheet serial 150300026300J R01 SDP
* Product code: Hub
* Board version: R01
* Boot loader: 0.1.7-BT (Thu Nov 30 09:45:22 2017)
* Firmware: v0.43.01.15019-BT
* GUI version: 1.80 11_07_2023
* The rear of the board is silk-screened with SMT S/N 


Overview
![Board](img/IMG_3075.jpg "Overview")
Overview left
![Board L](img/IMG_3052.jpg "Overview L")
Overview right
![Board R](img/IMG_3053.jpg "Overview R")

Rear overview
![Board Rear](img/IMG_3049.jpg "Rear Overview")
Rear overview left
![Board Rear L](img/IMG_3050.jpg "Rear Overview L")
Rear overview right
![Board Rear R](img/IMG_3051.jpg "Rear Overview R")


## SoC
- BCM63138 (RVKFEB) high-performance multimedia gateway SoC
- (with G.fast DSL)
- (FRAME 2)
- [Source Reference](https://opensource.actiontec.com/t3200m.html)
![SoC](img/IMG_3071.jpg "SoC")
![SoC](img/IMG_3079.jpg "SoC")


## NAND Flash 512MB
- Kioxia TC58BVG2SOHT A00 4Gbit 3.3V
- [Datasheet](DST_TC58BVG2S0HTA00-TDE_EN_31454.pdf) available from [here](https://www.kioxia.com/content/dam/kioxia/newidr/productinfo/datasheet/201910/DST_TC58BVG2S0HTA00-TDE_EN_31454.pdf)
- (FRAME 6 Board Rear)

![NAND](img/IMG_3067.jpg "NAND")


## Working Memory
- Micron D9SHD
- Micron part number MT41K256M16TW-107
- DRAM DDR3 4G 256MX16 FBGA IT LV V00H
- (FRAME 1)
- [Datasheet](MT41K1G4_MT41K512M8_MT41K256M16_RevR_Sep2018.pdf)
- [Datasheet](https://www.alldatasheet.com/datasheet-pdf/pdf/527111/MICRON/MT41K256M16.html)

![Frame 1](img/IMG_3073.jpg "Frame 1")


## USB
- 1 x USB-A socket connector (J4)
![Board Edge](img/IMG_3057.jpg "Board Edge")
![USB](img/IMG_3058.jpg "USB")


## 5GHz Radio 1
- BCM4366EKMMLW1G
- 5GHz 802.11ac 1024QAM
- (FRAME 4)

![Radio1](img/IMG_3064.jpg "Radio1")
![Radio1](img/IMG_3081.jpg "Radio1")


## 5GHz Radio 2
- BCM4366EKMMLW1G
- 5GHz 802.11ac 1024QAM
- (FRAME 3)

![Radio2](img/IMG_3080.jpg "Radio2")


## 2.4GHz Radio
- BCM43602KMLG
- 5GHz (capable) 802.11ac 256-QAM
- (FRAME 2)
![2.4G](img/IMG_3070.jpg "2.4G")


## Line Drivers
### MSC Micro SemiConductor Le87281
- G.Fast Single Channel Line Driver
- [Datasheet](DS_Le87281_Ver5_PreLim-PD-000298422.pdf) available from [here](https://www.microchip.com/content/dam/mchp/documents/LCLD/ProductDocuments/DataSheets/DS_Le87281_Ver5_PreLim-PD-000298422.pdf)

### DSL Line Driver
- BCM6303 KMLG
 - VDSL 17A (Annex A + Annex B )
 - VDSL 30A (Annex A + Annex B )
 - VDSL 35B (Annex A + Annex B )
 - 6KV

![DSL_LD](img/IMG_3083.jpg "DSL Line Driver")


## LEDs
- 2 x multicolour LEDs (LED1, LED2)
- (FRAME 6)
![LEDs](img/IMG_3076.jpg "LEDs")

- 1 x multicolour LED (LED3)
- (board edge)
![LED](img/IMG_3078.jpg "LED")


## Buttons
- 1 x Wireless WPS PTM
![Join Button](img/IMG_3055.jpg "Wireless Join Button")

- 1 x Factory Reset PTM (SW2)
![Reset Button](img/IMG_3054.jpg "Factory Reset Button")


## Telephony
- DSP Group DCX81 DECT 
- DCX81 AC0CFAE3FNC
- (FRAME 5)
- [Circuit Design](DCX81_CMBS_DESIGN_REV6_0.pdf) available from [here](https://www.synaptics.com/products/wireless/ule/ule-developers)
- [Reference PCB Design](DCX81_CMBS_DESIGN_REV6_0_PCB.pdf) available from [here](https://www.synaptics.com/products/wireless/ule/ule-developers)
- [ULE starter kit](https://github.com/DSPGroup/ule-starterkit/releases/tag/v1.0)
- DSP [Datasheet](DCX81-data-brief.pdf)
- Synaptics [Datasheet 2](synaptics-DCX81-product-brief.pdf)

![DECT](img/IMG_3068.jpg "DECT")


## Flash Memory (for DCX81 DECT chip)
- Winbond 25Q16JWS Serial NOR Flash 16MB
- (FRAME 5)
- [Datasheet](W25Q16JW_RevG_06302021_Plus.pdf) available from [here](https://www.winbond.com/hq/support/documentation/levelOne.jsp?__locale=en&DocNo=DA00-W25Q16JW)

![DECT NOR](img/IMG_3066.jpg "DECT NOR")

## Telephony POTS SLIC
- Si32176-ZM1
- Telecom IC Subscriber Line Interface Concept (SLIC), CODEC 42-QFN (5x7)
- [Datasheet](Si3217x-C.pdf) available from [here](https://www.skyworksinc.com/-/media/Skyworks/SL/documents/public/data-sheets/si3217x-c.pdf)
![POTS SLIC](img/IMG_3057.jpg "POTS SLIC")

