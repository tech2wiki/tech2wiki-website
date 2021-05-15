---
sort: 500
---

# Honk on lock

## Activate honk-confirmation on lock (Saab 9-5, Saab 9-3 -2003)

It’s possible to get a confirmation from the car that the car is successfully locked/alarmed. When this function is activated the car will honk the horn when you press the lock button twice. When you press the lock button twice the car will enter a mode called TSL (Theft Security Lock), this makes it impossible to open the car from the inside. When you only press the lock button once it’s still possible to open the doors from the inside. This function is programmed in the TWICE module.

### Requirements

* SAAB 9-5 MY98-10 or SAAB 9-3 MY98-02 (& -03 CV)
* Tech2 (CANDi module for SAAB 9-5 MY06 and newer)
* SAAB 1XX.000 PCMCIA card

### Procedure

* Select `F0`: Diagnostics
* Select Model Year
* Select `Saab 9-5` or `Saab 9-3`
* Select `F3`: Body
* Select `TWICE` (Theft Warning ICE)
* Select `F3`: Adjustment
* Select `Central Locking`
* Select `Sound Indication At TSL`
* Use the buttons to increase/decrease the time the horn should honk.
* The value can be set in steps of 5ms.
* The longer time you choose, the higher the sound of the honk will be.
* Press `OK to confirm the selected value.

