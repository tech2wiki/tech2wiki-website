---
sort: 100
---

# Changing SPA logic

Changing the logic of the SAAB Parking Assistence

## Enabling SPA for SAAB 9-3 2003-

If you have a SAAB 9-3 with model year 2003 and newer and don’t have an SPA on your car it can be retrofitted.

### Requirements

- SAAB 9-3 MY03 or newer
- SAAB Parking Assistance (SPA) Kit
- Tech2 with CANDi module
- Security Access
- SAAB 1XX.000 PCMCIA card

### Preparations

Install the kit according to the included [installation instructions](32026045gb.pdf).

To activate this function you will need security access which can be downloaded from TIS (TIS2000 or GlobalTIS).

### Procedure

- Select `F0`: Diagnostics
- Select Model Year
- Select `SAAB 9-3 Sport (9440)`
- Select `F4`: All
- Select `F7`: Add/Remove
- Select `F3`: Accessories
- Select `SPA`
- Select `Add` (If you haven’t downloaded security access from TIS yet, the Tech2 will prompt you to do)
- Exit out of the Tech2, cycle the key OFF and back ON and the function should now be enabled.
