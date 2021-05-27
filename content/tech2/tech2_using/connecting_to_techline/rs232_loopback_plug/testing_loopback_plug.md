---
sort: 200
---
# Testing the RS232 loopback plug

Test the plug by attaching it to the serial port of the Techline computer or into a certified Tech2 USB-2-serial adapter. Download a serial terminal application like RealTerm to diagnose the loop-back functionality.

Now plug your RJ-45 loop-back adapter into the Tech2 device and navigate to the RS-232 test. Depending on the software version there are various options to get to the RS-232 test menu.

While using the (SAAB 44.000 .bin file)[/content/which_.bin-files_are_available/SAAB.html] you need to follow this procedure;

*   Insert the loop-back plug into the RJ-45 port
*   Press `PWR` to turn on the Tech2
*   Title screen, press `ENTER`
*   `F2`: Tools Options
*   `F3`: Field Services Diagnostics
*   `F3`: Selectable Main PCB
*   `F2`: RS-232 LoopBack

While using the (SAAB 148.000 .bin file)[/content/which_.bin-files_are_available/SAAB.html] you need to follow this procedure;

*   Insert the loop-back plug into the RJ-45 port
*   Press `PWR` to turn on the Tech2
*   Title screen, press `ENTER`
*   `F2`: Tool Options
*   `F0`: Tech2 Self Test
*   Press `EXIT` on the notification screen
*   `F3`: Selectable Main PCB
*   `F2`: RS-232 LoopBack

Now the Tech2 should respond with the following: `RS-232 Test: Passed`

If the Tech2 responds with RS-232 Test: `LoopBack Not Connected` or `ADDRESS ERROR - PROCESSOR HALT` the chances are high that the MAX202 or the MAX232 is borked, which means replacing the SMD mountec RS-232 communications chip (SOIC type), noted as U202 on the main PCB.

Reference: [The three dudes and their cars…](https://dudes.berrydejager.com/tech2-rs-232-loopback-not-connected)