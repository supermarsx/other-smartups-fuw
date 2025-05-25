Version:
========
UPS 15.7

Applicable Models:
==================

SRT8KXLI
SRT8KXLT
SRT8KXLT-IEC 
SRT8KRMXLI
SRT8KRMXLT
SRT8KRMXLT-IEC
SRT10KXLI
SRT10KXLT
SRT10KXLT-IEC
SRT10KRMXLI
SRT10KRMXLT
SRT10KRMXLT-IEC
SRT10RMXLIX806
SRT10KXLTTW
DLRT8KRMXLI
DLRT8KRMXLT
FJRT8KXLI
FJRT10KXLI

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
	(a) UPS_12.0 and above versions supports Auto XBP Firmware upgrade feature under BMC firmware mismatch condition.	  
	(b) UPS_12.0 and above versions improves firmware upgrade functionality by using stable two step upgrade process.
	(c) UPS_12.0 and above versions enables Firmware upgrade process using USB Flash drive.
	Note: UPS ID 1021 currently doesn't support firmware upgrade with UPS output ON feature.
	      UPS ID 1021 is not compatible with older UPS ID 1002/1014.
	      1002/1014 ID firmware is till UPS_05.2.
	      1021 ID Firmware start from UPS_12.0. 

Note:
=====
Web Link for causes for Smart-UPS firmware upgrade to timeout - https://www.apc.com/us/en/faqs/FA410710/

Release Notes (UPS 15.7):
========================

SRT8KXLI, SRT8KXLT, SRT8KXLT-IEC, SRT8KRMXLI, SRT8KRMXLT, SRT8KRMXLT-IEC, SRT10KXLI, SRT10KXLT, SRT10KXLT-IEC, SRT10KRMXLI, SRT10KRMXLT, SRT10KRMXLT-IEC, 
SRT10RMXLIX806, SRT10KXLTTW, DLRT8KRMXLI, DLRT8KRMXLT:

1. Improved the reliability of the firmware upgrade process under certain conditions : "Comm Event: To Pwr Off" and repeated firmware installations.

Release Notes (UPS 15.6):
========================

SRT8KXLI, SRT8KXLT, SRT8KXLT-IEC, SRT8KRMXLI, SRT8KRMXLT, SRT8KRMXLT-IEC, SRT10KXLI, SRT10KXLT, SRT10KXLT-IEC, SRT10KRMXLI, SRT10KRMXLT, SRT10KRMXLT-IEC, 
SRT10RMXLIX806, SRT10KXLTTW, DLRT8KRMXLI, DLRT8KRMXLT:

1. Improved battery thermal detection.
	      
Release Notes (UPS 15.5):
========================

SRT8KXLI, SRT8KXLT, SRT8KXLT-IEC, SRT8KRMXLI, SRT8KRMXLT, SRT8KRMXLT-IEC, SRT10KXLI, SRT10KXLT, SRT10KXLT-IEC, SRT10KRMXLI, SRT10KRMXLT, SRT10KRMXLT-IEC, 
SRT10RMXLIX806, SRT10KXLTTW, DLRT8KRMXLI, DLRT8KRMXLT:

This revision provides stronger network data security protection via the below mechanisms to prevent malicious firmware from being upgraded to the UPS through communication interface ports (including RJ45).

Change logs:
1. The mechanism of firmware signing adds to the code in order to protect the UPS from malicious firmware spoofs. Based on the above, firmware upgrade via NMC is re-enabled.
2. Addressed battery pack numbering change under certain conditions during UPS firmware upgrade.

Release Notes (UPS 15.0):
========================

SRT8KXLI, SRT8KXLT, SRT8KXLT-IEC, SRT8KRMXLI, SRT8KRMXLT, SRT8KRMXLT-IEC, SRT10KXLI, SRT10KXLT, SRT10KXLT-IEC, SRT10KRMXLI, SRT10KRMXLT, SRT10KRMXLT-IEC, 
SRT10RMXLIX806, SRT10KXLTTW, DLRT8KRMXLI, DLRT8KRMXLT:

1. Addressed timeout event while receiving the UPS firmware file using NMC under certain conditions. Web link shown below:
	https://www.apc.com/us/en/faqs/index?page=content&id=FA411525 
	
2. This release includes remediations for the security vulnerabilities listed as CVE-2202-0715 which, 
	if compromised, may allow for potential unauthorized access and control of the device.
	Change logs:
		1. Function implemented to disable UPS firmware upgrades via NMC to mitigate potential risk of malicious UPS firmware being passed 
		   through this channel.
		2. Enhanced UPS firmware code protection to mitigate the vulnerabilities of unauthorized extraction of confidential firmware.

Release Notes (UPS 12.2):
========================

SRT8KXLI, SRT8KXLT, SRT8KXLT-IEC, SRT8KRMXLI, SRT8KRMXLT, SRT8KRMXLT-IEC, SRT10KXLI, SRT10KXLT, SRT10KXLT-IEC, SRT10KRMXLI, SRT10KRMXLT, SRT10KRMXLT-IEC, 
SRT10RMXLIX806, SRT10KXLTTW, DLRT8KRMXLI, DLRT8KRMXLT:
 
1. Improved system behavior to eliminate false triggering of Output distorted event.
2. Improved algorithm to detect Inverter Hardware Circuit event.
3. Improved system behvaiour for Miswired detection. 

Release Notes (UPS 12.0):
========================

SRT8KXLI, SRT8KXLT, SRT8KXLT-IEC, SRT8KRMXLI, SRT8KRMXLT, SRT8KRMXLT-IEC, SRT10KXLI, SRT10KXLT, SRT10KXLT-IEC, SRT10KRMXLI, SRT10KRMXLT, SRT10KRMXLT-IEC, 
SRT10RMXLIX806, SRT10KXLTTW, DLRT8KRMXLI, DLRT8KRMXLT:

1. ID is changed from 1002/1014 to 1021. 
Note: UPS ID 1021 is not compatible with older UPS ID 1002/1014.
2. Supports UPS Firmware upgrade using USB Flash drive. 
3. Improved UPS firmware upgrade functionality by using stable two step upgrade process.
4. point-3 in UPS_05.2 firmware release notes is not included in UPS_12.0 firmware. It will be added in the next firmware release. 

Release Notes (UPS 05.2):
=========================

SRT8KXLI, SRT8KXLT, SRT8KXLT-IEC , SRT8KRMXLI, SRT8KRMXLT, SRT8KRMXLT-IEC, SRT10KXLI, SRT10KXLT, SRT10KXLT-IEC, SRT10KRMXLI, SRT10KRMXLT, SRT10KRMXLT-IEC,
SRT10RMXLIX806, SRT10KXLTTW, DLRT8KRMXLI, DLRT8KRMXLT:
 
1. Addressed erroneous 'Battery Pack Disconnected' and 'Battery Pack Disconnected Cleared' events in the NMC log.
2. Improved algorithm to detect Inverter Hardware Circuit event.
3. Improved system behavior to eliminate false triggering of Output distorted event.
4. Improved algorithm to detect Back feed Relay weld event.
5. Improved capability to detect presence of internal battery in 'battery standby' state. 

Release Notes (UPS 05.1):
========================

SRT8KXLI, SRT8KXLT, SRT8KXLT-IEC , SRT8KRMXLI, SRT8KRMXLT, SRT8KRMXLT-IEC, SRT10KXLI, SRT10KXLT, SRT10KXLT-IEC, SRT10KRMXLI, SRT10KRMXLT, SRT10KRMXLT-IEC,
SRT10RMXLIX806, SRT10KXLTTW, DLRT8KRMXLI, DLRT8KRMXLT:

1. Improved system handling of over temperature conditions.
2. Changed wording for certain LCD status/warning messages.
3. Adjusted UPS power OFF control by increasing power button hold time to 5 seconds.

Release Notes (UPS 04.8):
========================

SRT8KXLI, SRT8KXLT, SRT8KXLT-IEC , SRT8KRMXLI, SRT8KRMXLT, SRT8KRMXLT-IEC, SRT10KXLI, SRT10KXLT, SRT10KXLT-IEC, SRT10KRMXLI, SRT10KRMXLT, SRT10KRMXLT-IEC,
SRT10RMXLIX806, SRT10KXLTTW, DLRT8KRMXLI, DLRT8KRMXLT:

1. Addressed false detection of 'Check Battery Cable' alarm under certain conditions.

Release Notes (UPS 04.7):
========================

SRT8KXLI, SRT8KXLT, SRT8KXLT-IEC , SRT8KRMXLI, SRT8KRMXLT, SRT8KRMXLT-IEC, SRT10KXLI, SRT10KXLT, SRT10KXLT-IEC, SRT10KRMXLI, SRT10KRMXLT, SRT10KRMXLT-IEC,
SRT10RMXLIX806, SRT10KXLTTW, DLRT8KRMXLI, DLRT8KRMXLT, FJRT8KXLI, FJRT10KXLI:

1. Improved system performance of transitions between Online and Bypass operation modes.
2. Improved system behavior for three phase input configuration to reduce transitions to battery under certain input
   feed conditions.
3. Improved system behavior to eliminate false detection of DC bus undervoltage alarm under certain conditions.
4. Improved system handling for certain AC input conditions during system startup.

Release Notes (UPS 04.6):
=========================

SRT8KXLI, SRT8KXLT, SRT8KXLT-IEC , SRT8KRMXLI, SRT8KRMXLT, SRT8KRMXLT-IEC, SRT10KXLI, SRT10KXLT, SRT10KXLT-IEC, SRT10KRMXLI, SRT10KRMXLT, SRT10KRMXLT-IEC,
SRT10RMXLIX806, SRT10KXLTTW, DLRT8KRMXLI, DLRT8KRMXLT:

1.  Improved system behavior to eliminate false detection of charger overvoltage alarm under certain load and battery conditions.

Release Notes (UPS 04.4):
=========================

SRT8KXLI, SRT8KXLT, SRT8KXLT-IEC , SRT8KRMXLI, SRT8KRMXLT, SRT8KRMXLT-IEC, SRT10KXLI, SRT10KXLT, SRT10KXLT-IEC, SRT10KRMXLI, SRT10KRMXLT, SRT10KRMXLT-IEC,
SRT10RMXLIX806, SRT10KXLTTW, DLRT8KRMXLI, DLRT8KRMXLT:

1.  Improved system behavior to eliminate false detection of "Power Sys Error - 00800" under certain load conditions.
2.  Improved system handling of over temperature conditions.
3.  Improved system performance for handling transition between utility and generator feeds.

Release Notes (UPS 04.3):
=========================

SRT8KXLI, SRT8KXLT, SRT8KXLT-IEC , SRT8KRMXLI, SRT8KRMXLT, SRT8KRMXLT-IEC, SRT10KXLI, SRT10KXLT, SRT10KXLT-IEC, SRT10KRMXLI, SRT10KRMXLT, SRT10KRMXLT-IEC,
SRT10RMXLIX806, SRT10KXLTTW, DLRT8KRMXLI, DLRT8KRMXLT:

1.  Improved battery charger response time during rapid ambient temperature changes.
2.  Updated battery replacement algorithm to handle batteries whose performance exceeds typical.

Release Notes (UPS 04.2):
=========================

SRT8KXLI, SRT8KXLT, SRT8KXLT-IEC , SRT8KRMXLI, SRT8KRMXLT, SRT8KRMXLT-IEC, SRT10KXLI, SRT10KXLT, SRT10KXLT-IEC, SRT10KRMXLI, SRT10KRMXLT, SRT10KRMXLT-IEC,
SRT10RMXLIX806, SRT10KXLTTW, DLRT8KRMXLI, DLRT8KRMXLT:

1.  Added support for the North American and Latin American skus; SRT8KXLT(-IEC), SRT8KRMXLT(-IEC), SRT10KXLT(-IEC), SRT10KRMXLT(-IEC).
2.  Improved THD performance for 3 phase input operation.
3.  Improved battery charger performance.
4.  Updated display messages when system components (Battery Packs) have incorrect firmware versions.
5.  Improved display messages during Firmware Upgrade process.
6.  Improved indication during low runtime conditions.
7.  Improved battery communication reliability when more than 5 external battery packs are used.
8.  Updated external battery pack firmware for compatibility with latest UPS firmware revision.

Release Notes (UPS 02.1):
=========================

SRT8KXLI, SRT8KXLT, SRT8KRMXLI, SRT8KRMXLT, SRT10KXLI, SRT10KXLT, SRT10KRMXLI, SRT10KRMXLT, SRT10RMXLIX806, SRT10KXLTTW, DLRT8KRMXLI, DLRT8KRMXLT:

1.  Update the run time prediction to include capacity of external battery packs.

Release Notes (UPS 01.8):
=========================
SRT8KXLI, SRT8KXLT, SRT8KRMXLI, SRT8KRMXLT, SRT10KXLI, SRT10KXLT, SRT10KRMXLI, SRT10KRMXLT, SRT10RMXLIX806, SRT10KXLTTW, DLRT8KRMXLI, DLRT8KRMXLT:

1.  Update the icons on the UI to represent IEC sockets.
2.  Improved bypass stability at low input voltages.
3.  Improved messaging and system behaviour for missing AC line neutral connection.







