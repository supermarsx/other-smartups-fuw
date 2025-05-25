Version:
========
UPS 15.7

Applicable Models:
==================
XU1K3LLXXRCC

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

Release Notes (UPS 02.7):
========================
1. Improved system behaviour for output voltage drop during firmware update under certain settings. 
2. Changed low ambient temperature threshold from 0 to -20DegC for charger operation.
CAUTION: ONLY THE BATTERIES CAPABLE OF CHARGING AT LOW TEMPERATURE UPTO –20 DEGREE C MUST BE CONNECTED TO THE UNITS HAVING FIRMWARE VERSION UPS_02.7 AND ABOVE.

Release Notes (UPS 02.6):
========================
1. Added configurable Battery Temperature lower and upper limits and Temperature Alert functionality for each relay in relay output setting.    
2. Improved battery voltage measurement under certain condition. 

Release Notes (UPS 02.5):
========================
1. Added event codes 245 and 246 for online and onbattery transfer in the logs.
2. Improved algorithm to detect fan event under certain conditions.
3. Addressed timeout event while receiving the UPS firmware file using NMC under certain conditions. Web link shown below:
	https://www.apc.com/us/en/faqs/index?page=content&id=FA411525   

Release Notes (UPS 02.3):
========================
1. Improved fan detection logic.
2. After firmware upgrade, unit is going to fan high speed, which is removed as it is not necessary.

Release Notes (UPS 02.2):
========================
1.Microlink map changed V2.0.2, removed BatterySystem.SKU_STR,HighEfficiency
OutputSystem.LowerAcceptableVoltageSetting and OutputSystem.UpperAcceptableVoltageSetting from map
2.Field issue-Fan inoperative issue, firmware logic implemented
3.Field issue-SOC not reaching 100% implemented
4.Battery Disconnect logic is improved, as because of the sensing issue in few units, 
unit is not detecting as battery disconnected when battery is removed
5.UPS-serial-Modbus configuration setting enabled from UI
6.Charger is ON,When Battery AH is selected to '0AH'.
Battery Temp sensor connected or disconnected, charger will be ON
7.Controlled Bypass pass through mode, on giving output off command when unit is in Online/Onbattery, load is not supported.

Release Notes (UPS 01.4):
========================
1.  Initial Release Pilot   