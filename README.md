Macropads made by yours trully



# This guide is for the tiny 100 buttons macropad
![image](https://github.com/backAir/Macropads/assets/72553201/87b6f4cb-7b76-447c-bb23-a1843d8bea52)

## Info
This macropad runs vial-qmk and has nkrl

if you want a PCB without the diodes you can either modify the PCB file or contact me

source code for the macropad is available [HERE](https://github.com/backAir/vial-qmk/tree/vial/keyboards/bair/mecropad10x10)


# What to buy ? 
Those are aliexpress links but ofc you can just buy it somewhere else:

100 buttons: [6x6x7 2 pin push buttons](https://aliexpress.com/item/1005006143327227.html) 

100 diodes : [IN4148 through hole diodes](https://aliexpress.com/item/32660088529.html) 

RP2040-Zero (VERY IMPORTANT: The version where the pins aren't soldered yet) : [RP2040-Zero](https://aliexpress.com/item/1005006031224378.html)

optional: PCB you can order on JLCPCB with the Gerber file downloadable [HERE](https://github.com/backAir/Macropads/releases/tag/v1.0.0), you can go without it if you want to handwire it


# Instruction for PCB assembly


if you're unsure about something ask me on discord my username is: back_air


make sure to read everything before doing anything ;)

Basically IN THIS EXACT ORDER:

- Solder all diodes above their icons (the stripe on the diodes needs to face the same dirrection as the stripes on the icon), solder them on the same same side as they are located to not interfere with the buttons

- Cut all of the excess metals rods with a flush cutter so the surface is flat.

- Solder the pins of the RP2040 onto the PCB but DON'T solder the RP2040 onto it's pins. The plastic should be on the opposite side of the diodes and the long part should be on the same side as the diodes. 

- Cut the excess metal that's on the same side as the diodes

- Solder all of the buttons and use the Printed top as a guide to keep the buttons alligned

- Solder the RP2040 onto it's pins while leaving the buttons facing away from the PCB, (cut off some metal from the buttons under the RP2040 if it's in the way)

- Flash the software using the uf2 file [HERE](https://github.com/backAir/Macropads/releases/tag/v1.0.0)  and have fun :)


# Instruction for Handwire:

ask me on discord: back_air
