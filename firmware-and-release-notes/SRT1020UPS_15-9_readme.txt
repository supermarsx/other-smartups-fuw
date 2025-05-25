Version:
========
UPS 15.9

Applicable Models:
==================

SRT5KXLI
SRT5KXLT
SRT5KXLT-IEC
SRT5KRMXLI
SRT5KRMXLT
SRT5KRMXLT-IEC
SRT6KXLI
SRT6KXLT
SRT6KXLT-IEC
SRT6KRMXLI
SRT6KRMXLT
SRT6KRMXLT-IEC
SRT5KRMXLW-TW
SRT5KRMXLW-HW
SMRT5KRMXLW-HW
SRT6KXLTW
DLRT5KRMXLI
DLRT5KRMXLT
SRT5KRMXLIM
SRT6KRMXLIM
SRT5KXLJ
FJRT5KXLI
DLRT5KRMXLJ
HTRT5KRMXLJ
FJRT5KRMXLJ
NCRT5KRMXLJ

Compatibility:
==============
FUW Tool version 4.2.0 and above required to upgrade the UPS:
	Web Link for downloading Latest FUW Tool and instructions to upgrade the UPS Firmware using FUW - https://www.apc.com/us/en/faqs/index?page=content&id=FA279197	
	UPS with firmware that allows firmware upgrade with output ON:	
		FUW Tool v4.2.1 and above will support firmware upgrade with both output OFF and output ON.
		FUW Tool v4.2.0 and below will support firmware upgrade only with output OFF.	
	Note: The Firmware Upgrade Wizard is the most reliable using RJ45 port; Upgrade via USB port from this tool is not recommended. 
		
	
NMC SUMX v6.5 and above required to upgrade the UPS:
	Web Link for instructions to upgrade the UPS Firmware using NMC - https://www.apc.com/us/en/faqs/FA170679/	
	UPS with firmware that allows firmware upgrade with output ON:
		NMC v6.5 will support firmware upgrade with both output OFF and output ON.
	Note: if NMC SUMX Version is below 6.5 version, Below Web link helps in upgrading the APC NMC Card with latest NMC SUMX version. 
		  Web Link for instructions to upgrade the firmware on an APC NMC Card - https://www.apc.com/us/en/faqs/index?page=content&id=FA156047

UPS & NMC Firmware upgrade using USB Flash drive:
	Web Link for instructions to upgrade the UPS Firmware using USB Flash drive - https://www.apc.com/us/en/faqs/content/?id=FA402857
	Note: (a) USB Flash drive should be of type FAT32 File system.
	      (b) Copy only one firmware file either NMC Firmware or UPS firmware in the USB Flash drive and initiate firmware upgrade one at a time.   
		
UPS firmware update compatibility: 		
	(a) UPS_10.1 and above versions enables Firmware upgrade process with UPS output ON feature. 	  
	(b) UPS_10.1 and above versions improves firmware upgrade functionality by using stable two step upgrade process.
	(c) UPS_10.1 and above versions supports Auto XBP Firmware upgrade feature under BMC firmware mismatch condition.
        (d) UPS_10.1 and above versions enables Firmware upgrade process using USB Flash drive.
	Note: UPS ID 1020 is not compatible with older UPS ID 1001/1013. 
	      1001 ID Firmware is till UPS_02.9 (Transit ENC converts from 1001 to 1013)
	      1013 ID Firmware is till UPS_05.1
	      1020 ID Firmare starts from UPS_10.1
Note:
=====
Web Link for causes for Smart-UPS firmware upgrade to timeout - https://www.apc.com/us/en/faqs/FA410710/

Release Notes (UPS 15.9):
========================

SRT5KXLI, SRT5KXLT, SRT5KXLT-IEC, SRT5KRMXLI, SRT5KRMXLT, SRT5KRMXLT-IEC, SRT6KXLI, SRT6KXLT, SRT6KXLT-IEC, SRT6KRMXLI, SRT6KRMXLT, SRT6KRMXLT-IEC, 
SRT5KRMXLW-TW, SRT5KRMXLW-HW, SMRT5KRMXLW-HW, SRT6KXLTW, DLRT5KRMXLI, DLRT5KRMXLT, SRT5KRMXLIM, SRT6KRMXLIM:

1. Improved the reliability of the firmware upgrade process under certain conditions : "Comm Event: To Pwr Off" and repeated firmware installations.

Release Notes (UPS 15.8):
========================

SRT5KXLI, SRT5KXLT, SRT5KXLT-IEC, SRT5KRMXLI, SRT5KRMXLT, SRT5KRMXLT-IEC, SRT6KXLI, SRT6KXLT, SRT6KXLT-IEC, SRT6KRMXLI, SRT6KRMXLT, SRT6KRMXLT-IEC, 
SRT5KRMXLW-TW, SRT5KRMXLW-HW, SMRT5KRMXLW-HW, SRT6KXLTW, DLRT5KRMXLI, DLRT5KRMXLT, SRT5KRMXLIM, SRT6KRMXLIM:

1. Improved battery thermal detection.

Release Notes (UPS 15.7):
========================

SRT5KXLI, SRT5KXLT, SRT5KXLT-IEC, SRT5KRMXLI, SRT5KRMXLT, SRT5KRMXLT-IEC, SRT6KXLI, SRT6KXLT, SRT6KXLT-IEC, SRT6KRMXLI, SRT6KRMXLT, SRT6KRMXLT-IEC, 
SRT5KRMXLW-TW, SRT5KRMXLW-HW, SMRT5KRMXLW-HW, SRT6KXLTW, DLRT5KRMXLI, DLRT5KRMXLT, SRT5KRMXLIM, SRT6KRMXLIM:

1. Enhanced logic to improve inverter event detection in specific conditions.
2. Addressed battery pack numbering change under certain conditions during UPS firmware upgrade.

Release Notes (UPS 15.5):
========================

SRT5KXLI, SRT5KXLT, SRT5KXLT-IEC, SRT5KRMXLI, SRT5KRMXLT, SRT5KRMXLT-IEC, SRT6KXLI, SRT6KXLT, SRT6KXLT-IEC, SRT6KRMXLI, SRT6KRMXLT, SRT6KRMXLT-IEC, 
SRT5KRMXLW-TW, SRT5KRMXLW-HW, SMRT5KRMXLW-HW, SRT6KXLTW, DLRT5KRMXLI, DLRT5KRMXLT, SRT5KRMXLIM, SRT6KRMXLIM:

This revision provides stronger network data security protection via the below mechanisms to prevent malicious firmware from being upgraded to the UPS through communication interface ports (including RJ45).

Change logs:
1. The mechanism of firmware signing adds to the code in order to protect the UPS from malicious firmware spoofs. Based on the above, firmware upgrade via NMC is re-enabled.


Release Notes (UPS 15.0):
========================

SRT5KXLI, SRT5KXLT, SRT5KXLT-IEC, SRT5KRMXLI, SRT5KRMXLT, SRT5KRMXLT-IEC, SRT6KXLI, SRT6KXLT, SRT6KXLT-IEC, SRT6KRMXLI, SRT6KRMXLT, SRT6KRMXLT-IEC, 
SRT5KRMXLW-TW, SRT5KRMXLW-HW, SMRT5KRMXLW-HW, SRT6KXLTW, DLRT5KRMXLI, DLRT5KRMXLT, SRT5KRMXLIM, SRT6KRMXLIM:

1. Addressed timeout event while receiving the UPS firmware file using NMC under certain conditions. Web link shown below:
	https://www.apc.com/us/en/faqs/index?page=content&id=FA411525 
	
2. This release includes remediations for the security vulnerabilities listed as CVE-2202-0715 which, 
	if compromised, may allow for potential unauthorized access and control of the device.
	Change logs:
		1. Function implemented to disable UPS firmware upgrades via NMC to mitigate potential risk of malicious UPS firmware being passed 
		   through this channel.
		2. Enhanced UPS firmware code protection to mitigate the vulnerabilities of unauthorized extraction of confidential firmware.
		
Release Notes (UPS 10.4):
========================

SRT5KXLI, SRT5KXLT, SRT5KXLT-IEC, SRT5KRMXLI, SRT5KRMXLT, SRT5KRMXLT-IEC, SRT6KXLI, SRT6KXLT, SRT6KXLT-IEC, SRT6KRMXLI, SRT6KRMXLT, SRT6KRMXLT-IEC, 
SRT5KRMXLW-TW, SRT5KRMXLW-HW, SMRT5KRMXLW-HW, SRT6KXLTW, DLRT5KRMXLI, DLRT5KRMXLT, SRT5KRMXLIM, SRT6KRMXLIM:

1. Improved system behvaiour for Miswired detection. 

Release Notes (UPS 10.1):
========================

SRT5KXLI, SRT5KXLT, SRT5KXLT-IEC, SRT5KRMXLI, SRT5KRMXLT, SRT5KRMXLT-IEC, SRT6KXLI, SRT6KXLT, SRT6KXLT-IEC, SRT6KRMXLI, SRT6KRMXLT, SRT6KRMXLT-IEC, 
SRT5KRMXLW-TW, SRT5KRMXLW-HW, SMRT5KRMXLW-HW, SRT6KXLTW, DLRT5KRMXLI, DLRT5KRMXLT, SRT5KRMXLIM, SRT6KRMXLIM:

1. ID is changed from 1001/1013 to 1020. 
Note: UPS ID 1020 is not compatible with older UPS ID 1001/1013.
2. Supports UPS Firmware upgrade using USB Flash drive. 
3. Support UPS firmware upgrade process with UPS output ON. 
Note: See compatibility notes for reference.
4. Improved UPS firmware upgrade functionality by using stable two step upgrade process.

Release Notes (UPS 05.1):
=========================
 
SRT5KXLI, SRT5KXLT, SRT5KXLT-IEC, SRT5KRMXLI, SRT5KRMXLT, SRT5KRMXLT-IEC, SRT6KXLI, SRT6KXLT, SRT6KXLT-IEC, SRT6KRMXLI, SRT6KRMXLT, SRT6KRMXLT-IEC, 
SRT5KRMXLW-TW, SRT5KRMXLW-HW, SMRT5KRMXLW-HW, SRT6KXLTW, DLRT5KRMXLI, DLRT5KRMXLT, SRT5KRMXLIM, SRT6KRMXLIM, FJRT5KXLI:

1. Addressed erroneous 'Battery Pack Disconnected' and 'Battery Pack Disconnected Cleared' events in the NMC log.
2. Improved algorithm to detect Inverter Hardware Circuit event.
3. Improved capability to detect presence of internal battery in 'battery standby' state.

SRT5KXLJ,FJRT5KRMXLJ:

1. Addressed erroneous 'Battery Pack Disconnected' and 'Battery Pack Disconnected Cleared' events in the NMC log.
2. Improved algorithm to detect Inverter Hardware Circuit event.
3. Improved capability to detect presence of internal battery in 'battery standby' state.
4. Addressed false detection of 'Check Battery Cable' alarm under certain conditions.
5. Improved battery charger profiling.
6. Adjusted UPS power OFF control by increasing power button hold time to 5 seconds.
7. Changed wording for certain LCD status/warning messages.
8. Addressed 'Last Battery Transfer' reporting status of "Unknown" under certain conditions.

Release Notes (UPS 05.0):
========================= 
SRT5KXLI, SRT5KXLT, SRT5KXLT-IEC, SRT5KRMXLI, SRT5KRMXLT, SRT5KRMXLT-IEC, SRT6KXLI, SRT6KXLT, SRT6KXLT-IEC, SRT6KRMXLI, SRT6KRMXLT, SRT6KRMXLT-IEC, 
SRT5KRMXLW-TW, SRT5KRMXLW-HW, SMRT5KRMXLW-HW, SRT6KXLTW, DLRT5KRMXLI, DLRT5KRMXLT, SRT5KRMXLIM, SRT6KRMXLIM:

1. Added optional PDU model SRT015 for SMRT5KRMXLW-HW SKU. 

Release Notes (UPS 04.8):
=========================
SRT5KXLI, SRT5KXLT, SRT5KXLT-IEC, SRT5KRMXLI, SRT5KRMXLT, SRT5KRMXLT-IEC, SRT6KXLI, SRT6KXLT, SRT6KXLT-IEC, SRT6KRMXLI, SRT6KRMXLT, SRT6KRMXLT-IEC, 
SRT5KRMXLW-TW, SRT5KRMXLW-HW, SRT6KXLTW, DLRT5KRMXLI, DLRT5KRMXLT, SRT5KRMXLIM, SRT6KRMXLIM:

1. Addressed false detection of 'Check Battery Cable' alarm under certain conditions.

Release notes (UPS 04.7):
=========================
SRT5KXLI, SRT5KXLT, SRT5KXLT-IEC, SRT5KRMXLI, SRT5KRMXLT, SRT5KRMXLT-IEC, SRT6KXLI, SRT6KXLT, SRT6KXLT-IEC, SRT6KRMXLI, SRT6KRMXLT, SRT6KRMXLT-IEC, 
SRT5KRMXLW-TW, SRT5KRMXLW-HW, SRT6KXLTW, DLRT5KRMXLI, DLRT5KRMXLT, SRT5KRMXLIM, SRT6KRMXLIM:

1. Improved battery charger profiling.
2. Enhanced unit output capacity with respect to output voltage selection for Cheetah XLT SKUs. 
3. Adjusted UPS power OFF control by increasing power button hold time to 5 seconds. 
4. Changed wording for certain LCD status/warning messages.
5. Addressed 'Last Battery Transfer' reporting status of "Unknown" under certain conditions.

Release notes (UPS 04.5):
=========================

SRT5KXLJ, DLRT5KRMXLJ, HTRT5KRMXLJ, FJRT5KRMXLJ, NCRT5KRMXLJ:

1. Support extended temperature ranges for Marine SKUs.
2. Improved sick and bad battery detection logic.
3. Improved output relay weld detection logic.
4. Output power enhanced for 5kVA XLT SKUs.
5. Updated default language setting for Japanese SKUs to be Japanese.
6. Improved DC Bus under voltage detection.
7. Improved inverter startup logic.
8. Improved system handling during battery over temperature condition.

Release Notes (UPS 04.1):
=========================
SRT5KXLI, SRT5KXLT, SRT5KXLT-IEC, SRT5KRMXLI, SRT5KRMXLT, SRT5KRMXLT-IEC, SRT6KXLI, SRT6KXLT, SRT6KXLT-IEC, SRT6KRMXLI, SRT6KRMXLT, SRT6KRMXLT-IEC, 
SRT5KRMXLW-TW, SRT5KRMXLW-HW, SRT6KXLTW, DLRT5KRMXLI, DLRT5KRMXLT, SRT5KRMXLIM, SRT6KRMXLIM:

1. Improved battery charger response time during rapid ambient temperature changes.
2. Updated battery replacement algorithm to handle batteries whose performance exceeds typical.
3. Improved bypass transfer response time at overloads.

Release Notes (UPS 04.0):
=========================
SRT5KXLI, SRT5KXLT, SRT5KXLT-IEC, SRT5KRMXLI, SRT5KRMXLT, SRT5KRMXLT-IEC, SRT6KXLI, SRT6KXLT, SRT6KXLT-IEC, SRT6KRMXLI, SRT6KRMXLT, SRT6KRMXLT-IEC, 
SRT5KRMXLW-TW, SRT5KRMXLW-HW, SRT6KXLTW, DLRT5KRMXLI, DLRT5KRMXLT:

1. Improved reliability of battery pack communication.
2. Improved battery charger performance.
3. Improved display messages during Firmware Upgrade process.
4. Improved EEPROM operations.
5. Added support for field replaceable PDU.
6. Improved energy metering in on battery state.
7. Improved system behavior at high battery temperature.
8. Improved display for output power reading.
9. Improved output frequency in on battery state.

Release Notes (UPS 02.6):
=========================
SRT5KXLI, SRT5KXLT, SRT5KXLT-IEC, SRT5KRMXLI, SRT5KRMXLT, SRT5KRMXLT-IEC, SRT6KXLI, SRT6KXLT, SRT6KXLT-IEC, SRT6KRMXLI, SRT6KRMXLT, SRT6KRMXLT-IEC, 
SRT5KRMXLW-TW, SRT5KRMXLW-HW, SRT6KXLTW, DLRT5KRMXLI, DLRT5KRMXLT:

1.  Update the run time prediction to include capacity of external battery packs.







