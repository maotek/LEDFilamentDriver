## LED Filament Driver board for controlling up to 10 LED filaments

![alt text](board.jpg)

KiCad project also contains a driver for EDP displays, however this schematic was not included in the final PCB.

---

BOM:

- STM32F103C6T6/STM32F103C8T6
- 10x AO3400 MOSFET SOT-23
- 13x 10K 0603
- 6x 100nF 0603
- 1x 470uF electrolytic cap
- 8 MHz crystal
- 2x 20pF 0603
- 1x AMS1117 3.3

---

AMS1117 3.3 is rated for 1A, make sure the LED filaments do no consume more than 1A.
