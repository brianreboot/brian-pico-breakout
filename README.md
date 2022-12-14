# Pico Breakout
This a simple Pico breakout PCB.

# Version 2
<img src="https://github.com/brianreboot/brian-pico-breakout/blob/main/Version%202/3D%20Renderings/front.png" height=30% width=30% > <img src="https://github.com/brianreboot/brian-pico-breakout/blob/main/Version%202/3D%20Renderings/back.png" height=30% width=30% >

# Specs
There's nothing really special about this board, it just takes the Pico and makes it easier to connect the 20-pin Brook Fighting stick harness to it. I made this as a personal project. You're going to need two 1206 4.7K Ohm pull-up resisters for the OLED. The L3 and R3 pins are optional, I added them to the board because there's a .1% chance that I may actually use them. The Pin Header spacing is 2.54mm.

# Getting the PCB made.
I get my PCBs made at <https://jlcpcb.com/>.  <br />
Just upload [pico_breakout_v2.zip](https://github.com/brianreboot/brian-pico-breakout/blob/main/Version%202/gerbers/pico_breakout_v2.zip) and use the default settings.

<img src="https://github.com/brianreboot/brian-pico-breakout/blob/main/jlcpcb%20pcb%20options/pcb%20options.png" height=30% width=30% >

# Firmware
This board requires a tweaked firmware that is based on the [Open Stick Foundation](https://github.com/OpenStickFoundation/GP2040-CE).<br />
To properly use this board then head over to my github <https://github.com/brianreboot/GP2040-CE> for the tweaked firmware. It has the same functionality except that the button layout on the OLED has been modified for the HRAP Premium VLX controller and pins rearranged on the Pico to for my PCB.

# License
CERN-OHL-W


