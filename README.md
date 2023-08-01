For instructions on green v1 boards see the [v1 tag](https://github.com/lukewakeford/DSLSwitchMod/tree/1.0)

I've sold out of boards at the moment, If I get anymore I will post [on instagram](https://instagram.com/applecorexy) about it and update [the eBay listing](https://www.ebay.co.uk/itm/134222632940)

# DSL Switch Mod v2.1
Enabling screen switching and making use of the the stylus holder location on your DS Lite / GB Macro.

![Top of v2.1 breakout board](https://imgur.com/VPYoRPQ.jpg)
![Bottom of v2.1 breakout board](https://imgur.com/PCYlm1t.jpg)

v2.1 includes all three switch functions and can be installed soldered or solderless.

![gif demo](https://i.postimg.cc/nVkH2QZT/ezgif-com-gif-maker.gif)
![Flex cable routing](https://imgur.com/XGzSk19.jpg)
![Top screen connector flex cable install](https://imgur.com/Z8QJAHW.jpg)

# If ordering your own boards
- If you want to use the same components as me, please see the BOM.csv file in the repo
- I ordered boards with the bottom half populated from jlcpcb. The gerber, bom and, pick and place files were accepted there just fine.
- The flex cable I use is a 25 pin 0.3mm pitch 120mm long ffc which i sourced from aliexpress

# To use this mod
You need to flash your ds lite with the tv out firmware mod *or* [buy a preflashed module](https://www.ebay.co.uk/itm/134222632940) - I recommend following [facelesstech's guide](https://bit.ly/3Nf0MW5) as he has gathered the most relevant information in one place. (the [bit.ly link](https://bit.ly/3Nf0MW5) on the board links to this guide)

If you buy a preflashed module you simply need to swap old for new, unplug the old module from the back of our DS Lite's motherboard and plug in the new.

![DS Lite BIOS/WIFI Module](https://i.imgur.com/RttTccL.png?1)

# Install Tips
- The 3D printed button cap can be simply pushed in to place from the inside of the case, sometimes it may be required to shave a small amount of plastic away where the cap meets the tact switch to adjust the clicky-ness. [v1.0 video example](https://www.youtube.com/shorts/EsnwIeIT36A)
- Use two of the original stylus tray screws (ones with the slight gold tint) to secure the breakout board in place. [v1.0 video example](https://www.youtube.com/shorts/EsnwIeIT36A)
- If soldering follow this pin out, I found that running wires underneath the ds game card slot is a good route for this.
![PIO](https://imgur.com/GY4ysrm.jpg)
- Please see the pictures at the top of this readme for the correct location to install the flex cable in the top screen connector port.
- If installing solderless you will need to allow the flex cable to fold somewhere underneath the battery. 
- Due to only using ~half of the top screen port it is possible to missalign the flex cable and the swtiches won't work - if this is the case - try again but ensure the flex cable is as far as it can go in to the port and to the right of the port.

# Sources:
- [facelesstech ds-lite-screen-switching-mod](https://facelesstech.wordpress.com/2021/06/20/ds-lite-screen-switching-mod/)
- [LostNintendoHistory Lost-NDS-TV](https://github.com/LostNintendoHistory/Lost-NDS-TV/tree/main/fwpatch)
