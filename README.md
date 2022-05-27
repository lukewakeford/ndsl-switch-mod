# :zap: I have a handful of boards and buttons for sale [on ebay.](https://www.ebay.co.uk/itm/134129032933)
However this repo should contain all the necessary files to order and or print your own.

# DSLSwitchMod
Adding a tactile switch in place of the stylus holder on your DS Lite / GB Macro.
The aim of this project was to make the hardware side of this mod much simpler, the required test point connections are printed on the board also, GND and P10

|![Top of breakout board](https://imgur.com/Ak9LxLe.jpg)|![Bottom of breakout board](https://imgur.com/YgcooIT.jpg)|
|---|---|
|![Assembly gif](https://imgur.com/RpcDlKr.gif)|![](https://imgur.com/xHNExd1.jpg)|

# To use this mod
You need to flash your ds lite with the tv out firmware mod - I recommend following [facelesstech's guide](https://bit.ly/3Nf0MW5) as he has gathered the most relevant information in one place. (the [bit.ly link](https://bit.ly/3Nf0MW5) on the board links to this guide)

After your firmware is ready, connect jumpers with the breakout board as below and you should have a working switch. *I found routing p10 under the cartridge port (following the old wifi antenna location) worked well to avoid the battery tray.*

![PIO](https://imgur.com/JZXk5wk.jpg)
![Complete wiring](https://imgur.com/U5ZYRJe.jpg)
![gif demo](https://i.postimg.cc/jSV3Z9h1/ezgif-com-gif-maker-5.gif)

# Sources:
- [facelesstech ds-lite-screen-switching-mod](https://facelesstech.wordpress.com/2021/06/20/ds-lite-screen-switching-mod/)
- [LostNintendoHistory Lost-NDS-TV](https://github.com/LostNintendoHistory/Lost-NDS-TV/tree/main/fwpatch)
