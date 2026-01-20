# kittenbyte-hackpad
https://blueprint.hackclub.com/hackpad

This is a my first project for hackclub and it is a 4-key macropad. It is a customizable keypad with four mechanical buttons designed to automate complex commands. It also has 2 WS2812B Leds, and uses QMK firmware.

## Features:
	- Has fusion 360 files for a case with a lid.
          (hackclub+hackpad.stp & hackclub+hakpad+top.stp)
	- 2 WS2812B RGB LEDs.
	- 4 Keys (2 X 2)
	- kicad files for pcb fab

## CAD Model:
Everything fits together using 5 M3 Bolts and heatset inserts. 4 for the case, one for the PCB. Also, it has a 5 degree tilt

It has 3 separate printed pieces. The angle, the base where the PCB sits, and the top cover. it also has 2 acrylic plates. One to cover the electronics, the other to hold the switches

<img src=assets/cad.png alt="Schematic" width="500"/>

Made in Fusion360. Nifty

## PCB
Here's my PCB! It was made in KiCad. The silkscreen was imported from a Figma image.

Schematic
<img src=assets/schematic.png alt="Schematic" width="300"/>

PCB
<img src=assets/pcb.png alt="Schematic" width="300"/>

I used MX_V2 for the keyswitch footprints. I think in retrospect, I should've added a ground plane
