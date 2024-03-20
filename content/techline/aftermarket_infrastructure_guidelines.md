---
sort: 300
---

# Aftermarket Infrastructure Guidelines

The computer connected to the Tech2 is referred to as the 'Techline terminal'. This machine runs the Tech2Win software on top of the Microsoft Windows operating system.

Daniel Clarkson wrote the [Aftermarket Infrastructure Guideline v1.0 PDF](aftermarket_infrastructure_guideline_v1.0.pdf),which was published by [ACdelco](https://www.acdelco.com/) in Januari 2021.

## Introduction

GM's hardware and software are designed and validated to work within specified hardware and software versions. This document details the ideal computer scenarios with which GM hardware and software will function as designed. Non-compliance could result in undesired results for which GM is not responsible and will not support.

## General Notes

The guidelines are organized as follows:
* __Good__ – the minimum acceptable systems capability/components for conducting diagnostics and programming with related GM hardware and software.

* __Better__ – the systems infrastructure capability/components that will deliver better performance and security while seeking to maximize the lifecycle of the investment.

* __Best__ – the systems infrastructure capability/components that will deliver best performance and security while seeking to maximize the lifecycle of the investment.

_NOTE: If you are looking to purchase new infrastructure, systems or solutions, please adhere to the specifications outlined in the "Better or Best" sections._

## Hardware
The following section details guidelines for required hardware and software as well as a guide for purchasing new hardware and software. NOTE: GM/ACDelco hardware and software must be utilized on a dedicated computer.

__Consumer-Grade__ versus __Enterprise-Grade__: Most computer manufacturers offer two different grades of computers: consumer-grade hardware intended for home and personal use, and enterprise-grade hardware intended for businesses. While the price of consumer-grade hardware may seem attractive for independent businesses, oftentimes the total cost of ownership ends up being greater due to the limited functionality, higher failure rates, and more complex support.

---

| SUPPORTED | NOT SUPPORTED |
| --- | --- |
| Enterprise grade hardware (PCs and Access Points) | Consumer grade hardware (PC and Access Points), Apple or Mac tablets & PCs<br>Non-branded, built by hand or thin client PC |
| Intel Core i3 / i5 / i7 processors 6th generation and above | ALL Intel Core i-series 5th generation and below Processors plus AMD, Celeron, Pentium and Atom processors |
| Windows 10 Professional, 64-bit | Windows 8.x, XP and Vista Business <br>Windows7 Professional, 32 and 64-bit<br>All Home Operating Systems<br>Tablets running Android or Mac operating systems |
| Java Run Time Environment 32 bit | All 64-bit versions of Java |

---

Questions related to the Aftermarket Guidelines can be directed to the
ACDelco helpdesk @888-212-8959.


## Desktop PC
| | Good | Better | Best |
| --- | --- | --- | --- |
| Processor | Intel Core i3, i5, i7 | 6th & 7th Gen Intel Core i3, i5, i7 8th Gen | Intel Core i5, i7 9th Gen & above |
| System memory (RAM) | 8GB | 16GB | 16GB |
| Hard Disk Drive<br>(HDD or SSD) | **256 GB + | 500 GB + | 1TB + |
| CD / DVD Drive | CD/DVD Combo |  CD/DVD Combo | CD/DVD Combo |
| USB A 2.0 & 3.0 | 2+ | 2+ | 2+ |
| Display | 20" 1366 x 768 (HD) | 22" 1920 x 1080 (FHD) | 24" 1920 x 1080 (FHD) |
| Network Adapter | Wired: Gigabit<br>Wireless: 802.11ac | Wired: Gigabit+<br>Wireless: 802.11ac | Wired: Gigabit+ Wireless: 802.11ax |
| Operating System | Windows 10 Professional, 64-bit | Windows 10 Professional, 64-bit | PC: Windows 10 Professional, 64-bit |
| Warranty | 3 Year on site | 3 Year on site | 3 Year on site |

* Note: 8th Generation or above have model numbers of 8000 or greater (example: Intel Core i5-8500).

_For the Techline Service Technician applications (TIS2Web, GDS2, MDI, MDI 2, Tech2Win, and Service Information):_

* Requires Local Windows Administrative access for software installation and updates to Windows registry
* Refer to page 9 for a list of recommended firewall and security exceptions
* Recommends one (1) Multiple Diagnostic Tool (MDI / MDI 2) for every PC
* Recommends one (1) battery maintainer for every two (2) Multiple Diagnostic Interface (MDI) tools in use
* Recommends use of Tripp-Lite Keyspan USB to Serial adapter (Model: USA - 19HS) for computers without serial ports

## Laptops & Tablet PCs
| | Good | Better | Best|
| --- | --- | --- | --- |
| Processor | Intel Core i3, i5, i7<br>6th & 7th Gen | Intel Core i3, i5, i7<br>8th Gen | Intel Core i5, i7 <br>9th Gen & above |
| System memory (RAM) | 8GB | 16GB | 16GB + |
| Hard Disk Drive<br>(HDD or SSD) | **256 GB + | 500 GB + | 750 GB + |
| CD / DVD Drive<br>(optional/external) | CD/DVD Combo | CD/DVD Combo | CD/DVD Combo |
| USB A 2.0 & 3.0 | 2+ | 2+ | 2+ |
| Display | 13" 1366 x 768 (HD) | 15" 1920 x 1080 (FHD) | 15+" 1920 x 1080 (FHD) |
| Network Adapter | Wired: Gigabit<br>Wireless: 802.11ac | Wired: Gigabit+<br>Wireless: 802.11ac | Wired: Gigabit+<br>Wireless: 802.11ax | 
| Operating System |Windows 10 Professional, 64-bit | Windows 10 Professional, 64-bit | Windows 10 Professional, 64-bit |
| Warranty | 3 Year on site | 3 Year on site | 3 Year on site |

* Note: 8th Generation or above have model numbers of 8000 or greater (example: Intel Core i5-8269U).
January 2021 Version 1.0

_For the Techline Service Technician applications (TIS2Web, GDS2, MDI, MDI 2, Tech2Win, and Service Information):_

* Requires Local Windows Administrative access for software installation and updates to Windows registry
* Refer to page 9 for a list of recommended firewall and security exceptions
* Recommends one (1) Multiple Diagnostic Tool (MDI / MDI 2) for every PC
* Recommends one (1) battery maintainer for every two (2) Multiple Diagnostic Interface (MDI) tools in use
* Recommends use of Tripp-Lite Keyspan USB to Serial adapter (Model: USA - 19HS) for computers without serial ports

## Software
| | Good | Better | Best|
| --- | --- | --- | --- |
| Web Browser<td colspan=3>Internet Explorer, version IE11 (with current Service Pack) with the "compatibility view" enabled<br>*See Microsoft Edge note below |
| Java<td colspan=3>Current 32-bit version of Java Runtime Environment, or the version recommended by each application |
| System Recovery<td colspan=3>Full Operating System Recovery Package,<br>Ensure the PC manufacturer or reseller provides the necessary recovery software to restore the operating system in the event of a major software failure. (Note: See Business Continuity Section) |
| Desktop Anti-Virus<td colspan=3>Enterprise Desktop Anti-virus solution that is updated automatically and managed through a centralized console. |

__Note__: As of October 2020, Microsoft will continue to support Internet Explorer 11 as a web browser for the duration of Windows 10. This is subject to change as Microsoft sees fit, and for the latest updates you can reference this website: [https://docs.microsoft.com/en-us/lifecycle/faq/internet-explorer-microsoft-edge](https://docs.microsoft.com/en-us/lifecycle/faq/internet-explorer-microsoft-edge). As Microsoft has announced, a shift to Microsoft Edge is under way. GM is working to make sure all applications function in Edge and at some point, Edge will be the primary browser.

## Internet Speed
| | Good | Better | Best|
| --- | --- | --- | --- |
| Speed | 100 Mbps | 1000 Mbps | 1000 Mbps |

__Note__:
The MDI and MDI 2 are not compatible with an open, unencrypted wireless network.

## Desktop Security
| | Good | Better | Best|
| --- | --- | --- | --- |
| PC Virus Monitoring<td colspan=3>Enterprise-grade, antivirus products should be installed on all PCs and configured to automatically perform the following:<br>* Download and install most current virus signature updates<br>* Actively monitor for viruses<br>* Quarantine and eradicate infected files<br>* Antivirus solution should include antivirus, anti-spyware, intrusion prevention, application control, spam control and rootkit detection |
| Patch Management<td colspan=3>* GM recommends that patch management be performed on every PC to ensure each workstation has current patches.<br>* Workstation Management should include remote monitoring of hardware/software failures, down servers, low disk space, excessive CPU usage and excessive memory usage. Install critical security patches within one month of release. |
| Password Protection<td colspan=3>Employees have multiple user ID’s and passwords used to access the tools that support user’s job roles. Implementing a password management policy is a significant piece of data security and access control.<br>All passwords should be promptly changed if suspected of/are being comprised, or disclosed to vendors for maintenance/support.<br>* Refrain from divulging passwords unless absolutely necessary (i.e., helpdesk assistance)<br>* Protect stored passwords – discourage employees from writing down access information and keeping it in plain sight of passerby (i.e., username & password written on post it note nearby workspace).<br>* Passwords should be encrypted when transmitted electronically.<br>* Passwords must be changed every 90 days.<br>* Users are not able to reuse their last five (5) passwords.<br>* User accounts are locked-out or suspended after the tenth (10) failed login attempts.<br>* Remove all employee credentials from all network devices immediately upon employment ending.

## GM Application Security and Firewall Exceptions
All application updates and installations must be performed from an account with local Windows administrative privileges. Firewall Exceptions for TIS2Web applications:
* 64-bit Windows:
    * C:\Program Files (x86)\Java\jre<version number>\bin\jp2launcher.exe
    * C:\Program Files (x86)\GDS 2\jre6\bin\javaw.exe
    * C:\Program Files (x86)\General Motors\Tech2Win\bin\emulator.exe
    * C:\Program Files (x86)\GM MDI Software\GM MDI Manager\GM_MDI_Manager.exe
    * C:\Program Files (x86)\GM MDI Software\GM MDI Identification Service\GM_MDI_Ident.exe
    * C:\Program Files (x86)\Vibe Programming\Cuw.exe
* 32 bit Windows:
    * C:\Program Files\Java\jre<version number>\bin\jp2launcher.exe
    * C:\Program Files\GDS 2\jre6\bin\javaw.exe
    * C:\Program Files\General Motors\Tech2Win\bin\emulator.exe
    * C:\Program Files\GM MDI Software\GM MDI Manager\GM_MDI_Manager.exe
 * C:\Program Files\GM MDI Software\GM MDI Identification Service\GM_MDI_Ident.exe
    * C:\Program Files\Vibe Programming\Cuw.exe
* Java Control Panel Security URL Exception:
    * https://tis2web.service.gm.com
* Internet Explorer Trusted Sites URL Exceptions:
    * *.gm.com