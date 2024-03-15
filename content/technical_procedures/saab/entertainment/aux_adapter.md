---
sort: 100
---

# AUX adapter

## Retrofitting an AUX adapter

SAAB 9-3 (code name: 9440, model year: 2003-2006) can have the AUX input retrofitted. This can be done at ICM1, ICM2 and ICM3 and the function must be activated with Tech2 after the adapter kit is installed.

### Requirements

- SAAB 9-3 (9440) MY03-06
- SAAB AUX Adapter Kit (OEM 32000102)
- Tech2 with CANDi module
- Security Access
- SAAB 1XX.000 PCMCIA card

### Preparations

It’s not necessary, but a good idea is to first install the AUX Adapter Kit (Installation instructions) in the car so you can test it right after the function is activated. The adapter kit can also be installed after the function is activated.

To activate this function you will need security access which can be downloaded from TIS (TIS2000 or GlobalTIS).

### Procedure

- Select `F0`: Diagnostics
- Select `Model Year`
- Select `Saab 9-3 Sport (9440)`
- Select `F4`: All
- Select `F7`: Add/Remove
- Select `F3`: Accessories
- Select `AUX-Input`
- Select `Add` (Tech2 may prompt for security access)
- Exit out of the Tech2
- Cycle the key OFF and back ON

The function should now be enabled. To enter AUX, use the `SRC`-button (Source) on the steering wheel or press the CD/Disc-button on the stereo unit twice.
