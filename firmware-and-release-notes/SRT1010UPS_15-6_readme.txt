Version:
========
UPS 15.6

Applicable Models:
==================

SRT2200XLI
SRT2200RMXLI
SRT2200RMXLI-NC
SRT3000XLI
SRT3000RMXLI
SRT3000RMXLI-NC
SRT3000XLT
SRT3000RMXLT
SRT3000RMXLT-NC
SRT3000XLW-IEC
SRT3000RMXLW-IEC
DLRT3000RMXLI

SRT2200XLA
SRT2200RMXLA
SRT3000XLA
SRT3000RMXLA
SRT2200RMXLA-NC
SRT3000RMXLA-NC
SRT3000XLA-TW
DLRT3000RMXLA

Compatibility:
==============
FUW Tool version 4.2.0 and above required to upgrade the UPS:
	Web Link for downloading Latest FUW Tool and instructions to upgrade the UPS Firmware using FUW - https://www.apc.com/us/en/faqs/index?page=content&id=FA279197	
	UPS with firmware that allows firmware upgrade with output ON:	
		FUW Tool v4.2.1 and above will support firmware upgrade with both output OFF and output ON.
		FUW Tool v4.2.0 and below will support firmware upgrade only with output OFF.	
	Note: (1) The Firmware Upgrade Wizard is the most reliable using RJ45 port; Upgrade via USB port from this tool is not recommended.
	      (2) After firmware upgrade the pop-up message "Firmware installation refused" may appear on the display and will automatically clear after few seconds.  
		      This message doesn't impact the firmware upgrade. 
		
NMC SUMX v6.5 and above required to upgrade the UPS:
	Web Link for instructions to upgrade the UPS Firmware using NMC - https://www.apc.com/us/en/faqs/FA170679/
	UPS with firmware that allows firmware upgrade with output ON:
		NMC v6.5 will support firmware upgrade with both output OFF and output ON.
	Note: if NMC SUMX Version is below 6.5 version, Below Web link helps in upgrading the APC NMC Card with latest NMC SUMX version. 
		  Web Link for instructions to upgrade the firmware on an APC NMC Card - https://www.apc.com/us/en/faqs/index?page=content&id=FA156047
		  
UPS firmware update compatibility:  
	(a) UPS_07.9 and above versions enables Firmware upgrade process with UPS output ON feature. 	  
	(b) UPS_07.9 and above versions improves firmware upgrade functionality by using stable two step upgrade process.
	(c) UPS_06.0 and above versions supports Auto XBP Firmware upgrade feature under BMC firmware mismatch condition.
    (d) UPS_07.9 and above versions ID will change from 1010 to 1025 after firmware upgrade.
	
Note:
=====
Web Link for causes for Smart-UPS firmware upgrade to timeout - https://www.apc.com/us/en/faqs/FA410710/

Release Notes (UPS 15.6):
========================

SRT2200XLI, SRT2200RMXLI, SRT2200RMXLI-NC, SRT3000XLI, SRT3000RMXLI, SRT3000RMXLI-NC, SRT3000XLT,
SRT3000RMXLT, SRT3000RMXLT-NC, SRT3000XLW-IEC, SRT3000RMXLW-IEC, DLRT3000RMXLI: 

SRT2200XLA, SRT2200RMXLA, SRT3000XLA, SRT3000RMXLA, SRT2200RMXLA-NC, SRT3000RMXLA-NC,
SRT3000XLA-TW, DLRT3000RMXLA:

1. Improved the reliability of the firmware upgrade process under certain conditions : "Comm Event: To Pwr Off" and repeated firmware installations.
	
Release Notes (UPS 15.5):
========================

SRT2200XLI, SRT2200RMXLI, SRT2200RMXLI-NC, SRT3000XLI, SRT3000RMXLI, SRT3000RMXLI-NC, SRT3000XLT,
SRT3000RMXLT, SRT3000RMXLT-NC, SRT3000XLW-IEC, SRT3000RMXLW-IEC, DLRT3000RMXLI: 

SRT2200XLA, SRT2200RMXLA, SRT3000XLA, SRT3000RMXLA, SRT2200RMXLA-NC, SRT3000RMXLA-NC,
SRT3000XLA-TW, DLRT3000RMXLA:

This revision provides stronger network data security protection via the below mechanisms to prevent malicious firmware from being upgraded to the UPS through communication interface ports (including RJ45).

Change logs:
1. The mechanism of firmware signing adds to the code in order to protect the UPS from malicious firmware spoofs. Based on the above, firmware upgrade via NMC is re-enabled.
2. Addressed battery pack numbering change under certain conditions during UPS firmware upgrade.

	
Release Notes (UPS 15.1):
========================

SRT2200XLI, SRT2200RMXLI, SRT2200RMXLI-NC, SRT3000XLI, SRT3000RMXLI, SRT3000RMXLI-NC, SRT3000XLT,
SRT3000RMXLT, SRT3000RMXLT-NC, SRT3000XLW-IEC, SRT3000RMXLW-IEC, DLRT3000RMXLI: 

SRT2200XLA, SRT2200RMXLA, SRT3000XLA, SRT3000RMXLA, SRT2200RMXLA-NC, SRT3000RMXLA-NC,
SRT3000XLA-TW, DLRT3000RMXLA:

1. Addressed 'Miswired' event under certain input conditions.

Release Notes (UPS 15.0):
========================

SRT2200XLI, SRT2200RMXLI, SRT2200RMXLI-NC, SRT3000XLI, SRT3000RMXLI, SRT3000RMXLI-NC, SRT3000XLT,
SRT3000RMXLT, SRT3000RMXLT-NC, SRT3000XLW-IEC, SRT3000RMXLW-IEC, DLRT3000RMXLI: 

SRT2200XLA, SRT2200RMXLA, SRT3000XLA, SRT3000RMXLA, SRT2200RMXLA-NC, SRT3000RMXLA-NC,
SRT3000XLA-TW, DLRT3000RMXLA:

1. Addressed timeout event while receiving the UPS firmware file using NMC under certain conditions. Web link shown below:
	https://www.apc.com/us/en/faqs/index?page=content&id=FA411525 
	
2. This release includes remediations for the security vulnerabilities listed as CVE-2202-0715 which, 
	if compromised, may allow for potential unauthorized access and control of the device.
	Change logs:
		1. Function implemented to disable UPS firmware upgrades via NMC to mitigate potential risk of malicious UPS firmware being passed 
		   through this channel.
		2. Enhanced UPS firmware code protection to mitigate the vulnerabilities of unauthorized extraction of confidential firmware.
		
Release Notes (UPSa08.3):
========================

SRT3000XLA-TW:

1. Improved capability to resume online operation at lower input voltage, after battery low shutdown.   
2. ID is changed from 1010 to 1025 after UPS Firmware Upgrade successfull.	
	  
Release Notes (UPS 08.3):
========================

SRT2200XLI, SRT2200RMXLI, SRT2200RMXLI-NC, SRT3000XLI, SRT3000RMXLI, SRT3000RMXLI-NC, SRT3000XLT,
SRT3000RMXLT, SRT3000RMXLT-NC, SRT3000XLW-IEC, SRT3000RMXLW-IEC, DLRT3000RMXLI: 

SRT2200XLA, SRT2200RMXLA, SRT3000XLA, SRT3000RMXLA, SRT2200RMXLA-NC, SRT3000RMXLA-NC,
SRT3000XLA-TW, DLRT3000RMXLA:

1. Improved sub-system version compatibility for SRT1010UPS_08.2.enc File. There is No change in system performance. 
2. ID is changed from 1010 to 1025 after UPS Firmware Upgrade successfull.


Release Notes (UPS 08.2):
========================

SRT2200XLI, SRT2200RMXLI, SRT2200RMXLI-NC, SRT3000XLI, SRT3000RMXLI, SRT3000RMXLI-NC, SRT3000XLT,
SRT3000RMXLT, SRT3000RMXLT-NC, SRT3000XLW-IEC, SRT3000RMXLW-IEC, DLRT3000RMXLI: 

SRT2200XLA, SRT2200RMXLA, SRT3000XLA, SRT3000RMXLA, SRT2200RMXLA-NC, SRT3000RMXLA-NC,
SRT3000XLA-TW, DLRT3000RMXLA:

1. Addressed erroneous 'Battery Pack Disconnected' and 'Battery Pack Disconnected Cleared' events in the NMC log.
2. Improved algorithm to detect Inverter Hardware Circuit event.
3. Improved capability to detect presence of internal battery in 'battery standby' state.
4. ID is changed from 1010 to 1025 after UPS Firmware Upgrade successfull.

Release Notes (UPS 07.9):
========================

SRT2200XLI, SRT2200RMXLI, SRT2200RMXLI-NC, SRT3000XLI, SRT3000RMXLI, SRT3000RMXLI-NC, SRT3000XLT,
SRT3000RMXLT, SRT3000RMXLT-NC, SRT3000XLW-IEC, SRT3000RMXLW-IEC, DLRT3000RMXLI:

1. Improved system handling of over temperature conditions.
2. Changed wording for certain LCD status/warning messages.
3. Addressed false detection of 'Check Battery Cable' alarm under certain conditions.
4. Support UPS firmware upgrade process with UPS output ON. 
Note: See compatibility notes for reference.
5. Improved UPS firmware upgrade functionality by using stable two step upgrade process.
6. Support Auto XBP Firmware upgrade feature under BMC firmware mismatch condition.
7. Adjusted UPS power OFF control by increasing power button hold time to 5 seconds. 
8. ID is changed from 1010 to 1025 after UPS Firmware Upgrade successfull.

SRT2200XLA, SRT2200RMXLA, SRT3000XLA, SRT3000RMXLA, SRT2200RMXLA-NC, SRT3000RMXLA-NC,
SRT3000XLA-TW, DLRT3000RMXLA:

1. Improved system handling of over temperature conditions.
2. Changed wording for certain LCD status/warning messages.
3. Addressed false detection of 'Check Battery Cable' alarm under certain conditions.
4. Support UPS firmware upgrade process with UPS output ON. 
Note: See compatibility notes for reference.
5. Improved UPS firmware upgrade functionality by using stable two step upgrade process.
6. Adjusted UPS power OFF control by increasing power button hold time to 5 seconds. 
7. ID is changed from 1010 to 1025 after UPS Firmware Upgrade successfull.






