---
sort: 1
---
# What is a Tech2?

The Tech2 is a scanning device which is able to let you deep dive into the internals of the various systems in your vehicle. While generic scanners can show and decode error codes, the Tech2 has the ability to get into the details of the error. Also the Tech2 is able to set brand/type specific settings. The Tech2 is not a engine tuning tool but is able to give you good insights on the status of the car. 

Vetronix made the Tech1. The original GM Tech2 was made by Hewlett Packard and used Vetronix software. Vetronix purchased the Tech2 manufacturing rights from HP. In 2003, Vetronix was acquired by ETAS, a supplier of standardized development and diagnostic tools for electronic control units. In 2006, the Vetronix Aftermarket division merged with Bosch Automotive Aftermarket, responsible for supply, sales and logistics of automotive parts for service of the vehicle. So today the Tech2 is ‘made’ by Bosch.

There a two major Tech2 line setups:

Tech2
*   Hardware scanner
    *   Tech2 device
    *   Tech Line PC

Tech2Win
*   Software scanner
    *   T2W cable
    *   Tech Line PC
    *   Tech2WIN software

## Tech2 

AD 400 Tech2 Scan tool

The ‘Daddy’ of all special SAAB tools, however, is the AD 400 Tech2 Scan tool. In effect, this is a hand held computer which uses PCMCIA cards onto which software is loaded for the appropriate GM family model \(SAAB, Vauxhall, Suzuki etc\). The scan tool is connected to the vehicle via the On Board Diagnostic \(OBD\) or CANBUS \(controller area network bus\) socket and draws power from the car.

It is hard to work on SAAB cars regularly without access to a Tech2 scan tool because the engine management systems have evolved since the days of the early 9000. Then, turning on the ignition and waiting for the management light to flash a certain number of times gave technicians a good idea what was wrong.

Now, cars like the 9-5 have two interconnected bus systems: iBus and pBus. The iBus is basically concerned with instrumentation while the pBus related to the power unit, monitoring the engine and transmission. Sensors on the pBus are interrogated all the time by the Trionic management system and if an unexpected value is returned or no signal is received, a diagnostic trouble code \(DTC\) is triggered.

The Tech2 can retrieve DTCs: example P1805 and they can be looked up with the Workshop Information System \(WIS\) in the case of 9-5s or with later 9-3s, it pays to have the Tech2 connected directly to a laptop, so the fault can be read directly by WIS.

In addition to being able to retrieve and clear DTCs, a Tech2 can also be used to reset service messages, alter locking logic, recalibrate the speedometer \(when 16“ wheels are changed to 17” or vice versa\), clone security chips for keys or update engine management software. A common need for a Tech2 arises when a SAAB is being dismantled – it is pointless recovering the radio/cd/cassette head unit unless it has been divorced from the car it was originally fitted to. Head units are married to individual cars and cannot be unlocked or decoded after they have been removed. A Tech2 is required, of course, to marry a unit that has been divorced from another car to a different vehicle. Be advised that a Tech2 kit with extras and software will cost around £3000 – for this reason, dealers will habitually charge owners for reading or clearing fault codes.

If you decide you cannot undertake a specific job on your SAAB without using special tools, you need to consider whether it isn’t more prudent to engage a SAAB specialist to carry out the job for you. This is because the tools are fairly pricey and are unlikely to be held in the UK \(special order\). Suppliers advise us that there is likely to be a long lead time for tools because there is no way to escape expensive carriage costs and the only sensible way to go is to place a consolidated order for a number of tools.

_Source: [SeriousSAAB](http://www.serioussaab.co.uk/articles_pages/special.html)_

##Tech2Win

Tech2Win is a PC program that executes Tech2 software on a Windows PC. Tech2Win communicates with a vehicle through a vehicle communication interface (VCI), using the MDI or an ISO 22900 PDU API compliant device.

Almost all vehicle systems supported by Tech2 will also work with the Tech2Win. The same software downloaded and executed on Tech2 will also run on Tech2Win. For that reason, the TIS2Web communication procedures used for Tech2 are also applicable for Tech2Win.

Source: [blog on bd2tool.com](https://www.obd2tool.com/blog/2019/10/29/what-is-tech2win-and-tech2win-software-car-list/)