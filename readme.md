## Make sure you read the license, if you see anyone selling these, please send me a message.

MBC30 Flashcart inspired by retroreboot's MBC3 cartridge.

## Ordering

**OSHPark:** 

[Regular Version](https://oshpark.com/shared_projects/xqcPwiVB)

[Crystal Clear Version](https://oshpark.com/shared_projects/qh5Q5MuF)

Make sure to select the "2 oz copper, 0.8mm thickness" option before checkout


**JLCPCB:**

Upload gerbers(.zip files) to [JLCPCB](http://jlcpcb.com)

Make sure you order with the following settings:

PCB Thickness: 0.8

PCB Color: Any

Surface Finish: ENIG-RoHS

Gold Fingers: Yes (45° chamfered border)

Castellated Holes: No


**PCBWay:**

[Regular Version](https://www.pcbway.com/project/shareproject/MBC30_Flashcart___4MB___FRAM___RTC___Suicune_Edition_1.html)

[Crystal Clear Version](https://www.pcbway.com/project/shareproject/MBC30_Flashcart___4MB___FRAM___RTC___Crystal_Clear_Edition_1.html)

## BOM

| Reference        | Part Number           | Description  |
| ------------- |:-------------:| -----:|
| B1 | BK-6219-TR | CR2025 Coin Cell Retainer |
| C1, C2, C3, C6, C7 | 06033C104KAT4A | 0.1uF Capacitor |
| C4, C5 | CL10C150JB8NNNC | 15pF Capacitor |
| RAM | FM18W08 | 256kbit FRAM |
| R1 | ERJ-PA3J334V | 330K Ω Resistor |
| R2 | ERJ-PA3J103V | 10K Ω Resistor |
| R3 | ERJ-PA3J102V | 1K Ω Resistor |
| MBC30 | MBC30 | Get from real cartridge |
| U1 | BA6129AF | Buy or get from real cartridge |
| U2 | 74LVC1G332GV,125 | 3-input OR gate TSOP-6 |
| ROM | AM29F032 (4MB) or MBM29F033C (4MB) | 4MB Rom Chip TSOP-40 |
| X1 | R26-32.768-12.5-10PPM | R26 12.5pF 32.768 kHz Crystal |

Note: Capacitors and Resistor part numbers are suggestions, you can use other components with matching specs

On 1.4.1 boards the flash should be soldered the other way around, as the indicator is wrong

## Images

![Front](front.png)


![Back](back.png)

![CCBack](cc-back.png)


**Changelog:**

**1.1:**

- Rewired WE on the ROM chip to Pin 31 on the cart bus to fix an issue where it would not write to a bank.

**1.2:**

- Changed the PCB to fit inside Japanese Pokemon Crystal shells
- Added inverted silkscreen to the board to make it look more like the original
- Added Crystal Clear edition

**1.3:**

- The pinout for the MBC30 listed online is wrong, thanks to [Alex](https://github.com/insidegadgets) over at [InsideGadgets](https://shop.insidegadgets.com/) for providing a fixed MBC30 pinout.

- Removed the front silk screens as most manufacturers struggle to make it.

**1.3.1:**

- Moved C2 to make it easier to close the shell

**1.4:**

- Switched cart bus footprint to [djedditt's replica of an original one](https://github.com/djedditt/kicad-gamepaks)

- Replaced the flash chip footprint with a TSOP-40 footprint.

- Redid the ground plane by hand, it should now look much better.

- Moved the battery receptacle footprint 0.5mm to the left.

- Renamed Y1 to X1

- Removed JLCJLCJLC marking for OSHPark project.

**1.4.1:**

- Fixed missing trace for Ram_CS

**1.4.2:**

- Fixed a symbol kicad "rescued" causing the pinout to be backwards (this put the chip direction indicator in the wrong corner)

## Videos


**Makho Building Revision 1.3.1**

[![text](https://img.youtube.com/vi/wJTDsA5XWiE/0.jpg)](https://www.youtube.com/watch?v=wJTDsA5XWiE)


**Mizuho Building Revision 1.3**


[![text](https://img.youtube.com/vi/DfoEXSLMXps/0.jpg)](https://www.youtube.com/watch?v=DfoEXSLMXps)


**AndehX Building Revision 1.4.1**

[![text](https://img.youtube.com/vi/C_L1obcNi5A/0.jpg)](https://www.youtube.com/watch?v=C_L1obcNi5A)
