---
sort: 320
---

# Enabling/Disabling DRL (Daytime Running Lights) (Saab 9-3 2003-)

You may find the fact that from the factory, most of our cars come with the lights defaulted to ON in all positions of the dash exterior lighting switch. This adjustment cannot be found in the common adjustments, like in some other models. In order to change the values, we need to re-add the following 2 modules to the car: UEC (Under-Hood Electrical Center) and REC (Rear Electrical Center).

In order to modify the configuration of your DRL’s, follow this procedure.

## Requirements

* SAAB 9-3 MY03 or newer
* Tech2 with CANDi module
* Security Access
* SAAB 1XX.000 PCMCIA card

## Procedure

* Select F0: Diagnostics
* Select Model Year
* Select Saab 9-3 Sport (9440)
* Select F4: All
* Select F7: Add/Remove
* Select F1: Control Modules
* Select UEC (Underhood Electrical Center)
* Select Add
* Follow the on-screen instructions, when you get to the headlight part of the guide there will be several options.
    * To have DRL’s OFF among headlights, choose the option for that headlights should be on when the light selector is in ROW POS 2.
    * To have the headlights ON at all times choose ROW POS 0.
* The next step is to make the rear lights match the headlights.
* Select REC (Rear Electrical Center)
* Follow the on-screen instructions as you did for the UEC.
* Go back to the Diagnostics menu.
* Select F3: Body
* Select Exterior Lightning and Horn
* Select Fog Lights Front
* There will be three different setups to choose between
    * Select ROW POS 1 & 2 for the ability to have the fog lights ON when your headlights are on. (This will also allow the fog lights to remain on while the high beams are being used).
* Repear the same procedure for Fog Lights Rear
