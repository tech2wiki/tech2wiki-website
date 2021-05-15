---
sort: 240
---
# Replacing ECU

## Requirements
* Tech 2
* VIN of the original ECU
* VIN of the replacement ECU
* Contact details Holden to retrieve the four digit security code
* Four digit security code of the original ECU
* Four digit security code of the replacement ECU

## Getting Codes

* Install replacement ECU and using the Tech 2 go to module information. Find and write down replacement ECU VIN.
* Write down original ECU VIN.
* Call Holden and give them the two VIN's and get the four digit security code for each VIN.
* Once you have both security codes you are good to continue.

## Unlocking ECU

* With the original ECU installed in the car, select `ECU` on the Tech 2 and enter `Special Functions` > `Reset ECU`. Perform the ECU reset, following the instructions on the screen and using the security code of the original ECU that you got from Holden.
* Remove the original ECU from the vehicle and install the replacement ECU.
* With replacement ECU installed in the car, select `ECU` on the Tech 2 and enter `Special Functions` > `Reset ECU`. Perform the ECU reset, following the instructions on the screen and using the security code of the replacement ECU that you got from Holden.

## Linking replacement ECU

* Go to BCM > Special Functions > BCM to PIM link. Follow the steps on the Tech 2 to link the PIM and BCM and using the 4 digit security code for the original ECU/VIN.
* Go to ECU > Special Functions and perform a PIM to ECU link. Follow the steps on the Tech 2 and using the 4 digit security code for the original ECU/VIN.

## Finishing up

* Clear fault codes for;
    * BCM
    * PIM
    * ECU
