---
sort: 570
---

# Replacing TWICE

## Exchanging broken TWICE (SAAB 9-5, SAAB 9-3 -2003)

During one morning a SAAB 9-5 MY 2000 refused to open its doors with the remote key (‘banana style’). The day before it was operating just fine. Opening the vehicle was only possible by inserting the key in the driver’s door. Following abnormal behavior was observed when the key was in the ‘Ignition ON’ position after inserting the key in the ignition lock barrel:

* SID showed message `Key not accepted`
* A clicking noise (approx. 1 click per 2s) from below the passenger seat
* Electric controls of passenger seat were disabled
* No central locking, doors could not be opened from inside
* When the key was turned into ‘Starter ON’ position, the starter motor was not activated

Changing the battery of the remote didn’t work and after some research on the internet it was concluded that this behavior was related to the TWICE unit.

### Disclaimer

The writer is a SAAB enthusiast trying to help out other SAAB owners by describing own experiences as accurately as possible. However, no rights or whatever can be derived in case things don’t proceed as planned or that go wrong/fail based on what is described (or not described) in this tutorial. In no case any responsibility can be taken for the results of using this tutorial. If you have no experience with electronic devices or understanding of modern automotive electronics, please don’t take any risks and have this work realized by your SAAB garage or SAAB specialist.

### Requirements

In order to deal with the situation for a SAAB 9-5 MY98-2010, following parts and equipment should be present:

* Original key belonging to the car. It is assumed that the user of this tutorial is the owner of the car or is working on the car on behalf of the owner.
* Tech2 device (thanks for your support Berry and other fellow SAAB enthusiasts!)
* New or alternative replacement TWICE unit with same part number
* Key with transponder (incl. ‘banana’) which should already be married to the replacement TWICE unit from the donor car. If you don’t have this married key, further work is useless I was informed by a SAAB specialist.

Note: *the actual (passive) transponder is in the key, the remote itself is in the banana. This tutorial for the TWICE replacement process was written based on experience with this particular type of key. Though, it is known that there are also newer, more integrated key designs. It is not tested if the tutorial works for these new designs. The same is applicable for other TWICE units, with different part numbers. These have not been tested for this tutorial.*

### Preparations

Before programming the replacement TWICE, following preparations are recommended:
* Retrieve DTCs with Tech2
* Take your Tech2 and connect to the mating connector below the steering wheel and read DTCs:
* Select F0: Diagnostics
* Select Model year
* Select SAAB 9-3 or SAAB 9-5
* Select F4: All
* Select Read All DTC Information

In case of the subjected vehicle, this resulted in a list with all systems and the number of DTCs in each system:
* Select Trionic 7
* Message appeared: P1460 Immobilizer active
* Press Enter
* Select Twice (Theft Warning ICE)
* Messages appeared:
    * B1782 Immobilizer active
    * B2385 Transponder Key. Missing
    * B2055 TWICE Unit. Spare Part Programming Not Performed
    * B1780 Immobiliser Data. Invalid Data
    * B1510 Power Ground. Missing

For this particular occasion, also B2121, B2122, B1262 and B1800 in the PMM Power Mirror Memory section were observed, but it is not sure if these were old DTCs or new ones related to the broken TWICE.

In any case, the other DTCs confirmed that the TWICE was not operating as it should.
Check fuses

Check all fuses related to TWICE to exclude any other reason for TWICE disfunctioning.
Replacing the TWICE unit

Now it’s time to replace the TWICE unit. The TWICE is installed below the left front seat. Some people have been confronted with a soaked TWICE because of clogged AC drains or leakage of rain water. This particular TWICE failed without any special reason (The TWICE was opened for inspection, but no traces of moisture, water, corrosion etc.).

### Replacement involves following steps:

* Put the seat in the far rear position and remove the 2 Torx bolts at the front end of the rails
* Put the seat in the front position, put the back rest as far as possible to the front and remove the 2 Torx bolts located at the other end of the rails.
* IMPORTANT: OPEN THE HOOD AND DISCONNECT THE GROUND CABLE OF THE BATTERY.
* Take out the seat and place it where the feet of the passengers on the rear seat are normally located. Be careful with the wiring attached to the bottom of the seat, prevent any tension.
* Remove the lower door sill. Carefully pry the sill upwards starting at one end and slowly working towards the other side.

[![](exchanging_broken_twice-module_01.png)](exchanging_broken_twice-module_01.png)
    
* Take out the black square plastic caps at the front rail mounting positions that hold the carpet to the body, de-press the small plastic pin and carefully pry out the un-locked black plug.

[![](exchanging_broken_twice-module_02.png)](exchanging_broken_twice-module_02.png)

* Fold away the carpet in the direction of the steering wheel until the ventilation duct is visible.
* Remove the 10 mm plastic nut of the ventilation duct that is located above the TWICE unit.

[![](exchanging_broken_twice-module_03.png)](exchanging_broken_twice-module_03.png)

* Now the duct can be lifted sufficiently to access and remove the 3x 10 mm nuts holding the TWICE to the body.

[![](exchanging_broken_twice-module_04.png)](exchanging_broken_twice-module_04.png)

* Carefully rotate the locking lever of the connector housing and remove the connector.
* Take out the TWICE unit.
* Installation of the replacement TWICE is the opposite of removing. Don’t forget to reconnect the battery afterwards.

### Keys

Basically there are two ways to get your new TWICE with matching key working.

* Combine the banana and transponder of the new key with the lower housing and blade of the old key, matching the original ignition lock barrel. Use a vice and screwdriver to carefully split the key. Don’t damage the blade. Re-use the lower part of the old key and the transponder and banana of the new key. You typically only need to prepare 1 key like this, the other (original spare) key can be introduced via the normal procedure for marrying a key.

[![](exchanging_broken_twice-key_01.png)](exchanging_broken_twice-key_01.png)
[![](exchanging_broken_twice-key_02.png)](exchanging_broken_twice-key_02.png)
[![](exchanging_broken_twice-key_03.png)](exchanging_broken_twice-key_03.png)
[![](exchanging_broken_twice-key_04.png)](exchanging_broken_twice-key_04.png)

* Be lucky and the key that comes with your replacement TWICE fits in your existing ignition lock barrel. Be sure to test the key with the door locks also, just in case.

There are other options as well, which are out of scope for this document though.

### Procedure

The procedure for marrying the TWICE unit and keys involves 2 or 3 steps using Tech2:

* Step 1A: Immobilizer
* Step 1B: Spare parts programming of the replacement TWICE unit
* Step 2: Marrying keys to the new TWICE

In case the replacement TWICE unit comes from exactly the same donor car (same part number, same market, same number of doors, same alarm system, same interior etc.), step 1B might be skipped. In this case step 1B was skipped initially. Car started and worked fine after steps 1A and step 2, but some strange errors were present: trunk lock didn’t work properly, brake light failure message in SID. It turned out that, although same part number, the replacement TWICE came from a 4D instead of a 5D car. After performing step 1B everything worked as it should, without any errors.

### Step 1A: Immobilizer

* Hook up the Tech2 to the car. Make sure that the battery of the car is okay and that your headlights and other consumers are OFF to prevent any undesired intermediate battery drainage.
* Select `F0`: Diagnostics
* Select Model year
* Select `SAAB 9-3` or `SAAB 9-5`
* Select `F3`: Body
* Select `TWICE` (Theft Warning ICE)
* Message appears: `NO BUS SYSTEMS CAN BE CONTACTED`
* Insert your prepared key and set to position `Ignition ON`.

_Note:_ Use the key with the transponder and remote already mated to the replacement TWICE! Refer to Chapter Preparations/Keys.

* Select `Enter`
* Select `F2`: Immobilizer
* Select `Trionic 7`
* Message appears: `Security Wait Time Active, Please Wait! 210 seconds remaining`
* After 210 seconds, message appears: `Programming Immobilizer Please Wait… Unit is being programmed!`
* Select `OK`
* Message appears: `Note Fault code 1460 may be present in Trionic 7. Remember to clear this immediately after this programming is done.`
* Select `OK`
* Go back to the main menu and clear the DTC `1460`.

It should now be possible to start the engine and drive the car. Depending on any errors, it can be necessary to realize Step 1B.

### Step 1B: Spare parts programming of the replacement TWICE unit

* Hook up the Tech2 to the car, put key in `Ignition ON` position
* Select `F0`: Diagnostics
* Select Model year
* Select `SAAB 9-3` or `SAAB 9-5`
* Select `F3`: Body
* Select `TWICE` (Theft Warning ICE)
* Select `F4`: Programming
* Select `Spare Part Programming`
* Message appears: `Alarm System Check. Tech2 will check Siren, Glass Break Sensor and Tilt Sensor presence in the car. Follow the instructions on the screen. Note! If any Sensor or the Siren is disconnected, Tech2 is not able to detect it.`
* Select `OK`
* Message appears: `To proceed it is needed to have at least 1 remote learned to the car. To do: Press OK to proceed.`
* Press `Exit` if no learned remote is available.
* Select `OK` (assuming you have the remote already married to the replacement TWICE)
* Message appears: `Remove key from Ignition Lock and arm the alarm with remote`
* Perform above requested action
* Message appears: `Checking Alarm System. Remaining wait time … Please Wait!`
* Message appears: `Unlock the Car with the Remote Control and turn the ignition to ON.` 
* Press `OK` to continue.
* Perform above requested action
* Select `OK`
* Message appears: `NOTE!!! Now you have an error message in SID! Do NOT abort the Spare Parts Programming but remember to clear DTCs in TWICE after the programming is completed`
* Now a bunch of settings need to be selected:
    * `Market`
    * `Theft Alarm`
    * `Steering Wheel Position`
    * `Rear Heated Seat`
    * `Power Seat`
    * `Body Style`
    * `Engine Type`
    * `Extended Belt Reminder`
    * `Alarm Sound Indication`
    * `Alarm – glass break sensor`
    * `Tilt sensor`

* By pressing `Change` / `Scroll and Select`, the correct setting should be selected matching the car. To go to the next setting, press `OK` each time.
* Most settings are obvious. The ones regarding the glass break sensor and tilt sensor are more difficult to find out as there are different variants. Though, the system automatically detects whether these items are present or not. If you selected these items being present incorrectly and they are not, the system allows a correction at the end of the programming process.
* Message appears: `Programming Completed`
* Message appears: `NOTE.Fault codes are now present in TWICE.` Remember to clear this immediately after this programming is done.
* Select `OK`
* Go back to the main menu and clear the DTCs.

All should work now without any errors.

## Step 2: Marrying keys to the new TWICE

* Please follow the steps as described in the other tutorials here.
* Make sure that all of your other keys and remotes are present before you start the procedure with Tech2.
* This may also be a good time to exchange the batteries of the remotes to prevent any future issues.
