---
sort: 300
---
# RS-232 Loopback plug not connected

 When you have inserted the RS-232 plug first make sure that the RS-232 is functioning according to the specification.

## Creating a RS232 Loopback connector

*   Cut off an eight-pin connector about three inches from the end.
*   Number the pins 1 thru 8 as you like.
*   Splice the pin wire pairs as follows:
    *    1-3
    *    2-7
    *    4-5
    *    6-8

## Tech 2 keyboard and RS232 loopback self test

*   Attach (p/n 3000112) RS232 eight-pin loop back connector to left side port of Tech2.
*   Attach (p/n 3000095) cable to the VCI in the bottom on the TECH2.
*   Attach (p/n 3000109) loop back adapter to the other end of the cable.
*   Connect a 12vdc power source to the TECH2.
*   Press ENTER.
*   Select TOOL OPTIONS.
*   Select TECH 2 Self Test
*   Read the screen and press EXIT.
*   Select Automated Main and VCI.
*   Read the results.

## Testing the RS232 loopback plug
Test the plug by attaching it to the serial port of the Techline computer or into a certified Tech 2 USB-2-serial adapter. Download a serial terminal application like RealTerm to diagnose the loop-back functionality.

Now plug your RJ-45 loop-back adapter into the Tech 2 device and navigate to the RS-232 test. Depending on the software version there are various options to get to the RS-232 test menu.

While using the (SAAB 44.000 .bin file)[/content/which_.bin-files_are_available/SAAB.html] you need to follow this procedure;

*   Insert the loop-back plug into the RJ-45 port
*   Press `PWR` to turn on the Tech 2
*   Title screen, press `ENTER`
*   `F2`: Tools Options
*   `F3`: Field Services Diagnostics
*   `F3`: Selectable Main PCB
*   `F2`: RS-232 LoopBack

While using the (SAAB 148.000 .bin file)[/content/which_.bin-files_are_available/SAAB.html] you need to follow this procedure;

*   Insert the loop-back plug into the RJ-45 port
*   Press `PWR` to turn on the Tech 2
*   Title screen, press `ENTER`
*   `F2`: Tool Options
*   `F0`: Tech 2 Self Test
*   Press `EXIT` on the notification screen
*   `F3`: Selectable Main PCB
*   `F2`: RS-232 LoopBack

Now the Tech 2 should respond with the following: `RS-232 Test: Passed`

If the Tech 2 responds with RS-232 Test: `LoopBack Not Connected` or `ADDRESS ERROR - PROCESSOR HALT` the chances are high that the MAX202 or the MAX232 is borked, which means replacing the SMD mountec RS-232 communications chip (SOIC type), noted as U202 on the main PCB.

Reference: [The three dudes and their cars…](https://dudes.berrydejager.com/tech2-rs-232-loopback-not-connected)