### File Instructions ###

JSON files are compatible with JLCPCB's EasyEDA.
https://easyeda.com/

.ZIP files contain all Gerber files for the associated version.
Gerber files are checked against the EasyEDA DRC (Design Rule Checker) and present no issues.

### Circuit Manufacturing ###

The circuit can be ordered for production by JLCPCB or PCBWay.
It should be developed at 1.6mm board thickness.
Colour is personal choice (black is the coolest though)
All other options left default.
I have tried getting them developed at 1.0mm thickness but they are not as rigid and can cause the fret buttons to appear angled when fully installed.

Spacers/washers and longer screws are required to fix the board back to the plastic fret plate.
Spacers can be 3D printed using the file "Spacer03.stl", or you can stack normal metal washers, but this is far more difficult to assemble.
If the board is printed at a different thickness, the spacers/washers will need to change thickness to accomodate.

### Instructions for modifying Logitar ###

  #### Remove fret buttons ####
  You will need to remove at least the Green, Yellow and Orange buttons.
  Under the buttons, there are 6 screws holding the plastic fret plate to the neck of the guitar.
  To remove fret buttons, apply pressure to one side of the fret button at the top or bottom, and use a sharp point to get some grip and       prise up the button. It should just pop out.
  I've done it with a screwdriver but I've found a sharp knife is more reliable.

  #### Unscrew the fret plate ####
  Remove the 6 screws attaching the fret plate to the neck of the guitar.
  The fret plate will lift out, and the fret board will be attached with 3 screws that run through vertically down the board.
  One at the top, one in the middle, and another at the bottom.

  #### Remove the fret board ####
  Remove the 3 screws holding the board to the fret plate.
  There will also be a blue plastic membrane which is a part of the membrane keyswitch mechanism.

  #### De-solder the existing board ####
  !!! TAKE NOTE OF THE WIRING LAYOUT !!!
  I advise taking photos of the existing board, so it is clear how the wires are supposed to be soldered.
  One side of the ribbon cable has a red stripe, which can be used to orient the cables if necessary.
  The existing fret board is attached with 8 wires that are part of a ribbon cable that runs down into the neck of the guitar.
  The cable is fragile and so are the solder connections.
  De-solder the cable using a solder vacuum pump or a desoldering braid.
  (My preference by far is the braid)
  Set aside the fret board.

  #### Hollow out the guitar neck ####
  This part is the scary part, and modifies the guitar permanently.
  Using a chisel or a router, you must make the inside of the neck completely uniform.
  From factory, the guitar neck has a large slot cut out, which is where the existing board and keyswitch assembly sit.
  Under that, there is a deeper notch.
  You must hollow out the larger notch so it is the same depth as the deeper notch.
  This can be done without damaging the guitar externally.
  There is a lot of material in the neck, and the guitar remains strong after this modification.
  If done correctly, you would not even be able to tell it has been done once the guitar is re-assembled.

  #### Solder switches to the new board ####
  The new board is designed to accept low profile keyswitches which can be purchased from hobbycnc.com.
  They are inexpensive, so I suggest getting a few different kinds to try.
  Tbe PCB order is generally a minimum of 5, so you may want to have multiple boards with different switches.
  The board is designed to have the switches inserted on the side of the board that does not have the tracks.
  The soldered pins will be located on the side of the board where the tracks are clearly printed.
  
  #### Solder the ribbon cable to the new board ####
  Using your prior photos as reference, re-solder the new board.
  The order for the wires on the new board is the same as the old board.

  #### Attach the new board using spacers ####
  The new board will need to be screwed back to the fret plate, using spacers on each of the three screws to separate the board from the       plate. Otherwise, the buttons will be too close to the switches and the switches will be pressed constantly.
  The spacers allow the switches to have room to actuate up and down.

  #### Attach the fret plate to the guitar body ####
  The fret plate can now be screwed back into the neck of the guitar.
  Be careful to use screws that are just long enough, otherwise you risk penetrating the guitar neck, causing externally-visible damage.
  If too short, the fret plate may become detached from the neck.
  The ribbon cable needs to be tucked away carefully and tightly, or it will cause the fret plate to bulge.

  #### Attach the buttons ####
  The fret buttons pop back in easily with a little pressure.
  You should be able to feel the buttons actuate the switches once they are installed.

  ### Troubleshooting ###
  The main issue I ran into is getting the cable tucked away properly so the fret plate attached properly.
  You may also find the board is at an angle since the screws attaching the fret board to the fret plate are only centred.
  This can be corrected by ensuring the board has pressure against the bottom of the guitar neck slot, giving the board some support and       stability.

