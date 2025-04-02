---
sort: 200
---
# Installing GlobalTIS

This section maps out the installation of the GlobalTIS 

## Description

GlobalTIS is manufactured by General Motors Europe

GlobalTIS is the predecessor of the TIS2000 software. This software can be used in combination with the Tech2 device.

## Requirements minimum

* Windows XP - 32 bits
* PDF reader

## Recommended software setup

* [Windows 7 - 32 bits](https://www.microsoft.com)
* GlobalTIS 2011 / 148
* [Ninite installer](https://ninite.com/)
  * [7-Zip](https://www.7-zip.org/)
  * [FireFox](https://www.mozilla.org/firefox/)
  * [Foxit Reader](https://www.foxitsoftware.com/pdf-reader/)
  * [NotePad++](https://notepad-plus-plus.org/)
  * [PuTTY](https://www.putty.org/)

## Installing steps

### GlobalTIS version 2010 \(146\) and version 2011 \(148\)

1. Start `Setup.exe` from the GlobalTIS installation media.
2. Select your preferred language, default is "English".
3. `Introduction`; click `Next`.
4. `License Agreement`; Read carefully and select `I accept the terms of the License Agreement` and click `Next`.
5. `Choose install Folder`; Select a destination folder, default `C:\Program Files\GlobalTIS`, click `Next`.
6. `Select Parameter Value`; _Installation type:_ `standalone`, click `Next`.
7. `Select Parameter Value`; _Host:_ `localhost`, click `Next`.
8. `Select Parameter Value`; _Transbase Server Port:_ `5024`.
9. `Select Parameter Value`; _Transbase Kernel Port:_ `5025`, click `Next`.
10. `Select Parameter Value`; _Tomcat Default Port:_ `9080`.
11. `Select Parameter Value`; _Tomcat HTTPS Port:_ `9090`.
12. `Select Parameter Value`; _Tomcat Shutdown Port:_ `9091`.
13. `Select Parameter Value`; _Tomcat AJP Port:_ `9092`, click `Next`.
14. `Select Parameter value`; _Mail Server:_ `[leave empty]`.
15. `Select Parameter value`; _Mail Port:_ `25`.
16. `Select Parameter value`; _User Name:_ `[leave empty]`.
17. `Select Parameter value`; _User Password:_ `[leave empty]`.
18. `Select Parameter value`; _Mail Sender:_ `[leave empty]`, click `Next`.
19. `Select Parameter value`; _Proxy Server:_ `[leave empty]`.
20. `Select Parameter value`; _Proxy Server Port:_ `[leave empty]`, click `Next`.
21. `Select Parameter value`; _Dealer Code \(BAC\):_ `[leave empty]`, click `Next`.
22. `Pre-Installation Summary`; Review the summary and click `Install`.
23. `Please Wait`; _This may take a moment._
24. `Install Complete`; _"Congratulations!"_ and click `Done`.

## Configuration steps

### Starting GlobalTIS

To start the GlobalTIS a new program is populated in the Start menu of windows.

* Start
  * All Programs
    * GlobalTIS
      * GlobalTIS

Starting the GlobalTIS will open a internet browser, which ever is the default.

This will start the GlobalTIS web page at: [http://localhost:9080/tis2web](http://localhost:9080/tis2web)

### Registration of GlobalTIS

1. Please fill in your dealership information by clicking on `Edit dealership data` and fill in the required fields;
   * _\*Dealership ID_ : `GlobalTIS`
   * _\*Dealership Name_ : `GlobalTIS`
   * _\*Street_ : `GlobalTIS`
   * _Zip / City_ : `GlobalTIS` \| `GlobalTIS`
   * _\*Location_ : `Afghanistan` \(default\)
   * _\*Language_ : `Albanian` \(default\)
   * _\*Contacts_ : _Name_ / _Language_ `GlobalTIS` \| `Albanian` \(default\), click `Save`
   * _Information: "M5009: Dealership data stored."_, click `Ok`
2. _Licensed users count_ : `1`
3. _Subscription_ : `SAAB`
4. Please register by clicking on `E-mail/Fax registration` in order to retrieve the registration details directly.
   * A PDF, containing the registration details, will be downloaded in your browser session.
   * Open this PDF.
   * Copy the `Software Key` to a text editor like `Notepad` or `NotePad++`
   * Make from the two lines of text a single line.

     **Online method**

   * Copy the URL `http://z90.pl/s_aab/gtis.php?x=` in front of the registration code.
   * Open another tab in the internet browser for 
     * Example URL `http://z90.pl/s_aab/gtis.php?x=B3AB-3724-8243-EB33-7A1E-E535-4DE9-8CE7-5F7D-955C-8986-9ED0-68EE-8249-0ACA-A9E4` 
   * This will return a JSON object containing the following information;

     * _key_ : `DC3F-9440-3D70-0F11-CE09-8874-FC23-FB5D-6993-23CC-44B0-1F9A-1CA5-A312-F0B0-364A`
     * _subscriber_ : `T987654321`
     * _hwid_ : `006D448BFF`
     * _installationtype_ : `STANDALONE`
     * _users_ : 0
     * _activation_ : `GME-SAAB`

     **Offline method**

   * \[insert method\]
5. Logout from this screen and start GlobalTIS again once you have received the license key. The registration process will then be continued with item 6.
6. Fill in the details gathered at point 4.
   * _Request ID_ : `(leave default)`
   * _Subscriber ID_ : `T987654321`
   * _License-Key_ : `DC3F-9440-3D70-0F11-CE09-8874-FC23-FB5D-6993-23CC-44B0-1F9A-1CA5-A312-F0B0-364A`
7. Please click the button 'Register License Key' to activate.
   * _Information: "M5014: The license key activation may take some time."_, click `Ok`
   * _License was registered and GlobalTIS has been activated. Please log-out \(terminate the session via the icon in the upper right hand corner\) and re-start GlobalTIS or log-in again._ and click on `Logout`
   * Note: when the registration fails please repeat from step 6.
