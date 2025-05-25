Version:
========
UPS 15.7

Applicable Models:
==================
XU2K0LLXXRCC


Compatibility:
==============
FUW Tool version 4.2.1 and above required to upgrade the UPS:
	Web Link for downloading Latest FUW Tool and instructions to upgrade the UPS Firmware using FUW - https://www.apc.com/us/en/faqs/index?page=content&id=FA279197
Note:FUW Tool v4.2.1 and above will support firmware upgrade with output ON.

NMC SUMX v6.8.2 and above is recommended to upgrade the UPS:
	Web Link for instructions to upgrade the UPS Firmware using NMC - https://www.apc.com/us/en/faqs/FA170679/	
	Note: if NMC SUMX Version is below 6.8.2 version, Below Web link helps in upgrading the APC NMC Card with latest NMC SUMX version. 
		  Web Link for instructions to upgrade the firmware on an APC NMC Card - https://www.apc.com/us/en/faqs/index?page=content&id=FA156047	

Web Link for instructions to upgrade the UPS firmware using USB:  https://www.apc.com/ca/en/faqs/index?page=content&id=FA402857

Web Link for pre-conditions which fails the UPS firmware upgrade installation:  https://www.apc.com/ca/en/faqs/index?page=content&id=FA410710

CAUTION: ONLY THE BATTERIES CAPABLE OF CHARGING AT LOW TEMPERATURE UPTO –20 DEGREE C MUST BE CONNECTED TO THE UNITS HAVING FIRMWARE VERSION UPS_02.7 AND ABOVE.


------------release history--------------

Release Notes (UPS 15.7):
========================
1. Improved the reliability of the firmware upgrade process under certain conditions : "Comm Event: To Pwr Off" and repeated firmware installations

Release Notes (UPS 15.6):
========================
This revision provides stronger network data security protection via the below mechanisms to prevent malicious firmware from being upgraded to the UPS through communication interface ports (including RJ45).

Change logs:
1. The mechanism of firmware signing adds to the code in order to protect the UPS from malicious firmware spoofs. Based on the above, firmware upgrade via NMC is re-enabled.

Release Notes (UPS 15.0):
========================
1. This release includes remediations for the security vulnerabilities listed as CVE-2202-0715 which, 
	if compromised, may allow for potential unauthorized access and control of the device.
	Change logs:
		1. Function implemented to disable UPS firmware upgrades via NMC to mitigate potential risk of malicious UPS firmware being passed 
		   through this channel.
		2. Enhanced UPS firmware code protection to mitigate the vulnerabilities of unauthorized extraction of confidential firmware. 
2. Improved system behaviour for output voltage drop during firmware update under certain settings. 
3. Changed low ambient temperature threshold from 0 to -20DegC for charger operation.
CAUTION: ONLY THE BATTERIES CAPABLE OF CHARGING AT LOW TEMPERATURE UPTO –20 DEGREE C MUST BE CONNECTED TO THE UNITS HAVING FIRMWARE VERSION UPS_02.7 AND ABOVE.
4. Improved battery voltage measurement under certain condition.
5. Added event codes 245 and 246 for online and onbattery transfer in the logs.
6. Added configurable Battery Temperature lower and upper limits and Temperature Alert functionality for each relay in relay output setting.  
7. Addressed timeout event while receiving the UPS firmware file using NMC under certain conditions. Web link shown below:
	https://www.apc.com/us/en/faqs/index?page=content&id=FA411525

Release Notes (UPS 00.3):
========================
1.Microlink map changed V0.1.2, removed BatterySystem.SKU_STR,HighEfficiency
OutputSystem.LowerAcceptableVoltageSetting and OutputSystem.UpperAcceptableVoltageSetting from map
2.Introduced state as Maintenance_Bypass, for installing with Bypass BOX through whcih load is ON
3.UPS-serial-Modbus configuration setting enabled from UI

Release Notes (UPS 00.2):
========================
1.  Initial Release Pre-pilot (engineering release).  