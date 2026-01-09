Fork of Tyeractive as a base to build my layout on top of for my Corne 2.1 Choc with Nice!Nano's and Nice!View's
https://github.com/typeractivexyz/corne-wireless-5-col-view-zmk-config

I've used the nickcoutsos/keymap-editor extensively to get my primary keymap setup:
https://nickcoutsos.github.io/keymap-editor/

The board is sourced from ergomechstore/Corne-chocoflan which enables access to built in support for battery and wireless via the Nice!Nano's, removes the trrs port, and adds native support for Nice!Views with 5 pins
https://github.com/ergomechstore/Corne-chocoflan
I had to jeryrig the power by soldering 2 cables to a ph connector as the original board has it set up to connect the battery to underneith the keyboard, I wanted the batteries to go under the Nice!Nano's so I could have an ultra-low profile

I 3D printed my own custom keyboard case, it has cut-outs for all the components, making the lowest point only 0.2mm off the table (hot-swap sockets).
I believe the case cut outs are close enough to the component to prevent the solder pads from being ripped off when pressing in the switches, which some have reported.

![First Final Hardware Build Image](https://github.com/woodknot/corne-wireless-5-col-view-zmk-config-Dvorak/blob/master/CorneBuild.png?raw=true)

I've learned of a custom keycap manufacturer for the choc keycaps, which I intend to use shortly, have made very few changes to my keymap the last year
https://fkcaps.com/
https://fkcaps.com/custom
At the time of writing I'm using the MBK Legend 40s Grey-on-White

I used jlcpcb to print my boards, they end up hitting you with more costs after the order claiming 'additional routing required', and the shipping goes up exponentially for adding components on, so I did all my own soldering
https://jlcpcb.com/

Keyboard Reseller parts:
1. Nice!Nano's
2. Nice!View's
3. Acrylic screen covers
4. Keycaps
5. Switches
6. Kailh hot-swaps sockets

Aliexpress parts:
1. Diodes
2. White stand-offs (for nice!nano, nice!view)
3. Pins to make the nice!nano and nice!view hot-swapable using the standoffs
4. White JST PH 2.0mm battery connectors
5. Reset buttons
6. Power slide switches
7. Round silver standoffs (for the screen acrylic covers)
8. Board to case bolts(screws?)/nuts
9. Board/Stand Off/Screen Cover screws
10. Magnetic usb-c adapters

Soldering tips:
1. Put a dot of solder on one of every pad, then using curved tweezers hold the component in the correct position and press the side down into the solder, then solder the other side
2. I bought a head magnifier off Amazon, it comes with about 6 glass lenses that clip into the front of it of different focal lengths, very useful for the diodes. Otherwise use protective glasses while soldering
3. Use a fume extractor, or what I did was buy a small rechargeable fan off Amazon and set it up to the side of me to blow the fumes away

To Do list (mainly need to learn KiCad):
1. Move the ph connector is on the top of the pcb so that I can connect the battery directly on the top
2. Move the reset switch to a switch on the side of the board that can be pressed, this will make using it with screen covers in place much easier. My keymap has bootloader keys so this is not really an issue

Back of my case, visably thin

![Ultra-low-profile Case is visibly thin](https://github.com/woodknot/corne-wireless-5-col-view-zmk-config-Dvorak/blob/master/CorneBuildCaseBack.png?raw=true)
