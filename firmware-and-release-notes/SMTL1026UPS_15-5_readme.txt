Version  UPS 15.5(SMTL)
Applicable SKUs
================
ID 1026, All standard SKUs beginning with SMTL prefixes.

SMTL SMTL750RM2UCNC, SMTL750RM2UC, SMTL1000RM2UC, SMTL1000RM2UCNC, SMTL1500RM3UC,SMTL1500RM3UCNC, 
     DLTL1500RM3UC, SMTL750RMI2UC, SMTL750RMI2UNC, SMTL1000RMI2U, SMTL750RMI2U, DLTL1500RMI3UC, 
     SMTL1500RMI3UC, SMTL3000RM2UC, SMTL3000RM2UCNC, SMTL3KRM2UCL, SMTL3KRM2UCLNC, SMTL3KR2C-NB, 
     SMTL3KR2CNC-NB, SMTL2200RM2UC, SMTL2200RM2UCNC, SMTL2K2RM2UCL, SMTL2K2RM2UCLNC, SMTL2K2R2C-NB, SMTL2K2R2CNC-NB, 

This revision revives the communication of the USB port while the UPS is on “suspend” mode when the PCBE starts recommunicating.

Change logs:
1.	Increase the detection of the USB D- signal to escape the “suspended”

Note: Smart-UPS Firmware Upgrade Wizard tool 
always includes the latest released firmware and helps upgrade the UPS code.
Link to tool - https://www.apc.com/us/en/faqs/FA279197/



Previous Released Version  UPS 15.1(SMTL)
Applicable SKUs
================
ID 1026, All standard SKUs beginning with SMTL prefixes.

SMTL SMTL750RM2UCNC, SMTL750RM2UC, SMTL1000RM2UC, SMTL1000RM2UCNC, SMTL1500RM3UC,SMTL1500RM3UCNC, 
     DLTL1500RM3UC, SMTL750RMI2UC, SMTL750RMI2UNC, SMTL1000RMI2U, SMTL750RMI2U, DLTL1500RMI3UC, 
     SMTL1500RMI3UC, SMTL3000RM2UC, SMTL3000RM2UCNC, SMTL3KRM2UCL, SMTL3KRM2UCLNC, SMTL3KR2C-NB, 
     SMTL3KR2CNC-NB, SMTL2200RM2UC, SMTL2200RM2UCNC, SMTL2K2RM2UCL, SMTL2K2RM2UCLNC, SMTL2K2R2C-NB, SMTL2K2R2CNC-NB, 


This revision provides stronger network data security protection via the below mechanisms to prevent malicious firmware from being upgraded to the UPS through communication interface ports (including RJ45).

Change logs
1.	The mechanism of firmware signing adds to the code in order to protect the UPS from malicious firmware spoofs. Based on the above, firmware upgrade via NMC is re-enabled. 
2.	Added the selection of FW Update Interfaces under the LCD Menu-Configuration. This can assist the user to decide whether or not firmware upgrades are allowed through designated communication ports.
3.	Changed TLS used for SmartConnect to MbedTLS for cybersecurity.

Note Smart-UPS Firmware Upgrade Wizard tool 
always includes the latest released firmware and helps upgrade the UPS code via serial(RS232) port; Upgrade via USB port from this tool is not recommended.
Link to tool - httpswww.apc.comusenfaqsFA279197



Previous Released Version  UPS 15.0
Applicable Models
==================
ID 1026, All standard SKUs beginning with SMTL prefixes.

SMTL SMTL750RM2UCNC, SMTL750RM2UC, SMTL1000RM2UC, SMTL1000RM2UCNC,SMTL1500RM3UC, SMTL1500RM3UCNC, 
     DLTL1500RM3UC, SMTL750RMI2UC, SMTL750RMI2UNC, SMTL1000RMI2U, SMTL750RMI2U, DLTL1500RMI3UC,SMTL1500RMI3UC, 
     SMTL3000RM2UC, SMTL3000RM2UCNC, SMTL3KRM2UCL, SMTL3KRM2UCLNC, SMTL3KR2C-NB, SMTL3KR2CNC-NB, SMTL2200RM2UC, 
     SMTL2200RM2UCNC, SMTL2K2RM2UCL, SMTL2K2RM2UCLNC, SMTL2K2R2C-NB, SMTL2K2R2CNC-NB, 


This release includes remediations for the security vulnerabilities listed as CVE-2022-22805, CVE-2022-22806 and CVE-2202-0715 which, 
if compromised, may allow for potential unauthorized access and control of the device.

Change logs
1.	Function implemented to disable UPS firmware upgrades via NMC to mitigate 
   	potential risk of malicious UPS firmware being passed through this channel.
2.	Enhanced UPS firmware code protection to mitigate the vulnerabilities of 
unauthorized extraction of confidential firmware and un-authorized network    access to SmartConnect UPSs.


Previous Released Version  UPS 02.9
Applicable Models
==================
ID 1026, All standard SKUs beginning with SMTL prefixes.

SMTL SMTL750RM2UCNC, SMTL750RM2UC, SMTL1000RM2UC, SMTL1000RM2UCNC,SMTL1500RM3UC, SMTL1500RM3UCNC, 
     DLTL1500RM3UC, SMTL750RMI2UC, SMTL750RMI2UNC, SMTL1000RMI2U, SMTL750RMI2U, DLTL1500RMI3UC,SMTL1500RMI3UC, 
     SMTL3000RM2UC, SMTL3000RM2UCNC, SMTL3KRM2UCL, SMTL3KRM2UCLNC, SMTL3KR2C-NB, SMTL3KR2CNC-NB, SMTL2200RM2UC, 
     SMTL2200RM2UCNC, SMTL2K2RM2UCL, SMTL2K2RM2UCLNC, SMTL2K2R2C-NB, SMTL2K2R2CNC-NB, 

Change logs
1	   Information revised in VoltageACSetting usage.
2     Information revised in UPSStatusChangeCause usage.
3.	Sequence improvement on exiting Green Mode.
4.	Add new SKUs support.


Previous Released Version  UPS 02.6
Applicable Models
==================
ID 1026, All standard SKUs beginning with SMTL prefixes.

SMTL SMTL750RM2UCNC, SMTL750RM2UC, SMTL1000RM2UC, SMTL1000RM2UCNC,SMTL1500RM3UC, 
     SMTL1500RM3UCNC, DLTL1500RM3UC, SMTL750RMI2UC, SMTL750RMI2UNC, SMTL1000RMI2U, SMTL750RMI2U, DLTL1500RMI3UC,SMTL1500RMI3UC,
      
Change logs
1.    Update version string for factory release



Previous Released Version  UPS 02.0
Applicable Models
==================
SMTL SMTL750RM2UCNC, SMTL750RM2UC, SMTL1000RM2UC, SMTL1000RM2UCNC,SMTL1500RM3UC, SMTL1500RM3UCNC, 
     DLTL1500RM3UC, SMTL750RMI2UC, SMTL750RMI2UNC, SMTL1000RMI2U, SMTL750RMI2U, DLTL1500RMI3UC,SMTL1500RMI3UC,

Change logs
  1.    Add support for 230 International SKUs
  2.    Hided the ethernet cable connection in setup wizard for non-SmartConnect SKUs
  3.    Hided Smart Connect Status display for non-SmartConnect SKUs
  4.    Improve runtime algorithm
  5.    Fix the SoC display issue in status menu




Previous Released Version UPS 01.5
Applicable Models
==================
SMTL750RM2UC, SMTL1500RM3UC
Change logs
1.    Added compatibility for SMTL1000RM2UC
2.    Improved the behavior of the system when operating at 50Hz.


Previous Released Release Notes (UPS 01.3)
Applicable Models
==================
SMTL750RM2UC, SMTL1500RM3UC
Change logs
1.    Added compatibility for SMTL750RM2UC
2.    Added support for Modbus over TCP on SmartConnect port
3.    Improved behavior with USB HID driver
4.    Updates to the LCD menu translations for improved clarity.
5.    Improved the reporting of temperature in °F on LCD
6.    Improved the behavior of system during a transfer back to utility power.



Initial Release Version UPS 01.0
Applicable Models
==================
SMTL1500RM3UC


Compatibility
==============
PCBE 9.5
AP9641AP9643 NMC3 su v2.2.0.1, aos v2.2.0.1, boot v1.4.2.1
AP9630AP9631 NMC SUMX 6.5.6
AP9624
AP9613
