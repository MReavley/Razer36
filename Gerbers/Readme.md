## BOM

2x PCB\ 
2x Seeeduino Xiao BLE\
2x Lipo Battery (I used 110mAh, not sure how much bigger you can get away with)\
2x PCM12 Switches\
6x 0603 SMD resistors (I tried 5.1K and they didn't work, ended up shorting them but low value resistors (probably 100Ohm) would be easier) \
36x SOD-123 Diodes\
36x Choc switches and keycaps of your preference\

## Build notes:
(Built and designed the keyboard ages ago so I'm going off memory here, but it is very similar to my Slice36 design)\
Designed around the right hand PCB, so the controller needs to be installed upside down on the left side. \
Remember to solder on the battery connector to the bottom of the Xiao before soldering the controller on (Battery + only). \
Battery ground goes to J3, through-hole near the powerswitch footprint. \
Powerswitch footprint can be found on either side of the PCB, so just solder on to the top side of the left and right side. \
Spare IO for I2C are routed to through-holes below the PCB, but are not used in my build. \

