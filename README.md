[Instructions for older board versions are available at the relevant tag](https://github.com/lukewakeford/ndsl-switch-mod/tags)

[Buy a kit on my website](https://www.lukewakeford.co.uk) or [Follow me on instagram for updates](https://instagram.com/applecorexy)

# DSL Switch Mod v3.0
A screen switch breakout board for the DS Lite / GB Macro - requires the TV Out Firmware Mod by [LostNintendoHistory Lost-NDS-TV](https://github.com/LostNintendoHistory/Lost-NDS-TV/tree/main/fwpatch)

![Top of v3.0 breakout board](https://imgur.com/8Aev7u5.jpg)
![Bottom of v3.0 breakout board](https://imgur.com/wgV2oBV.jpg)
![gif demo](https://i.postimg.cc/nVkH2QZT/ezgif-com-gif-maker.gif)
![Flex cable routing](https://imgur.com/XGzSk19.jpg)

# If ordering your own boards
- The components used should be available in the BOM.csv file.
- I ordered boards with the bottom half populated from jlcpcb using the gerber, bom and, pick and place files, then soldered on the switches myself.
- The flex cable I use is a 25 pin 0.3mm pitch 120mm long ffc which i sourced from aliexpress

# To use this mod
You need to flash your ds lite with the tv out firmware mod *or* [buy a kit](https://lukewakeford.co.uk/product/dsl-switch-mod-v3-0) - I recommend following [facelesstech's guide](https://bit.ly/3Nf0MW5) as he has gathered the most relevant information in one place. (the [bit.ly link](https://bit.ly/3Nf0MW5) on the board links to this guide)

# Install Tips
- After removing the stylus tray, The 3D printed button cap can be put in place from inside of the enclosure.
- Use two of the original stylus tray screws (ones with the slight gold tint) to secure the breakout board on top of the cap. [v1.0 video example](https://www.youtube.com/shorts/EsnwIeIT36A)
- If your buttons are not clicking, back off one or both of the mounting screws a tiny bit to adjust.
- If soldering follow this pin out
![PIO](https://imgur.com/GY4ysrm.jpg)
- I found that running wires underneath the ds game card slot is a good route for this.
- If installing using the flex cable it must be plugged in to right hand side of the top screen connector nearest pin 1, as pictured:
![Top screen connector flex cable install](https://imgur.com/Z8QJAHW.jpg)
- You will need to allow the flex cable to fold somewhere underneath the battery. 
- Due to only using ~half of the top screen port it is possible to missalign the flex cable and the swtiches won't work - if this is the case - try again but ensure the flex cable is as far as it can go in to the port and to the right of the port.

# Sources:
- [facelesstech ds-lite-screen-switching-mod](https://facelesstech.wordpress.com/2021/06/20/ds-lite-screen-switching-mod/)
- [LostNintendoHistory Lost-NDS-TV](https://github.com/LostNintendoHistory/Lost-NDS-TV/tree/main/fwpatch)
