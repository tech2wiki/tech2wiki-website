---
sort: 510
---

# Adding a key

Does your Saab 9-3 have exactly one key? This is known to be risky, and can be expensive: If you lose the last key you must buy another TWICE with at least one programmed key, then worry about lock cylinders, etc. A Tech-2 is necessary to replace the TWICE.

Even if you haven’t lost the only key, and just buy some new ones, you need the Tech-2 to add them to the car. Strictly speaking, one programs the car with a new list of keys, replacing the entire old list. One of the old keys must be present to begin (to prove you’re not a car thief), and all of the old and new keys must be present for this step. Any key not programmed into the car right now is forgotten and will no longer work to start the car. (It may open the doors, but that sets off the alarm.)

## These instructions are for the OG 9-3 (98-02+03CV)

eBay is a good source of used “remote keys” for this generation of 9-3, to get the “guts” (the remote transmitter, and transponder, with buttons). eEuroparts, among others, can sell you the shell, minus the guts, with the metal blade cut to the code for your VIN. Put those together, and you’re most of the way there. Ensure that all the keys you want to program have good batteries. For a used head it’s a bit hard to tell, since your car won’t pay any attention to it, so maybe replace it anyway. They take a CR1632. You’ll need a stout pin to unlatch the battery door on the back of the remote key head.

## To program a new set of keys

### All keys must be present, including at least one that is already programmed to the car

* Identify the UNLOCK button on the remote-key head so you can find it by feel.
* Connect the Tech-2 to the OBD-II port on the car.
* Turn the headlights OFF.
* Using one of the already-known keys, turn the ignition to ON so the Tech-2 can talk to the TWICE.
* Power on the Tech-2. Hit ENTER when prompted.
* Choose: Diagnostics / year / Saab 9-3 / Body / TWICE
    (Wait while Tech-2 establishes communications with the module.)
* Choose: Marry new keys (or words to this effect)

Follow the instructions on-screen. There are a couple of OK/NO pages, one of which is default EXIT. Then:

* Watch the red SEAT BELT light on the dashboard.
* On the key that is now in the ignition, hit the UNLOCK button once per second until the SEAT BELT light flashes. This may take up to 8 button pushes. If the light doesn’t flash, check the battery in the key, and start over.
* Turn OFF the ignition.
* If there are more keys: Insert the next key to be programmed, turn ON the ignition, and go to Step 2.
* Confirm with OK that all keys are programmed.
* Turn OFF and disconnect the Tech-2
