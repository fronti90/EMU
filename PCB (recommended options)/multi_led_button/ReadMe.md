## EMU LED PCB

The **EMU LED PCB** is a dedicated PCB designed for the EMU to enable dynamic lighting effects on the eject button assembly. It also simplifies wiring and reduces the need for soldering.

![LED PCB](https://github.com/user-attachments/assets/14425b43-296c-47e2-9205-70350bf1aeb9)

## BOM variations vs. baseline EMU BOM
Do not purchase the below from the base BOM:
1. 1 less neopixel
2. 1 less D2F-L switch
3. 4 less 6x3mm magnets

Add the below to the base BOM, depending on your LED PCB source:
1. 1x JST-XH 5 pin PCB header

## Manual
Assembly and wiring instructions are outlined [in the manual](https://github.com/DW-Tas/EMU/blob/main/PCB%20(recommended%20options)/multi_led_button/EMU%20LED%20Button%20PCB%20Assembly%20Manual.pdf).

## Sourcing
The hatch board PCBs can be sourced from the below location:
1. [Aliexpress](https://www.aliexpress.com/item/1005011529532141.html) in sets of 5

Alternatively use the supplied gerber, BOM and pick and place files to order from your favourite PCB manufacturer.

## Lighting effects
The multiple LEDs incorporated in the eject button allow you to create loading/unloading animations like the below. Also the integrated SMD switch provides a more tactile feel vs. the D2F switch and magnet assembly. 

The lighting effects are enabled automatically by happy hare. No separate configuration is required.

https://github.com/user-attachments/assets/2f268710-e0a5-41e1-b007-02235ff379cc



## This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## License clarification regarding non-commercial use:
The non-commercial aspect of this license is for cases where EMU is the product, not the use of EMU to create products.<br/>
I.e. If you wish to sell EMU as a product, you would need to seek a commercial license before doing so. </br>
It is NOT intended to prevent the use of EMU with a printer that you use to provide commercial services. If you want to run EMU in your print farm, go right ahead.

