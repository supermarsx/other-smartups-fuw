Version:
========
UPS 15.6

Applicable Models:
==================

SRT1000XLA
SRT1000RMXLA
SRT1500XLA
SRT1500RMXLA
SRT1000RMXLA-NC
SRT1500RMXLA-NC

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

UPS firmware update compatibility: 
	(a) UPS_07.1 and above versions enables Firmware upgrade process with UPS output ON feature. 	  
	(b) UPS_07.1 and above versions improves firmware upgrade functionality by using stable two step upgrade process.
	(c) UPS_07.1 and above versions supports Auto XBP Firmware upgrade feature under BMC firmware mismatch condition.
	(d) UPS_07.9 and above versions ID will change from 1019 to 1025 after firmware upgrade.
	
Note:
=====
Web Link for causes for Smart-UPS firmware upgrade to timeout - https://www.apc.com/us/en/faqs/FA410710/

Release Notes (UPS 15.6):
========================

SRT1000XLA, SRT1000RMXLA, SRT1500XLA, SRT1500RMXLA, SRT1000RMXLA-NC, SRT1500RMXLA-NC:

1. Improved the reliability of the firmware upgrade process under certain conditions : "Comm Event: To Pwr Off" and repeated firmware installations.

Release Notes (UPS 15.5):
========================

SRT1000XLA, SRT1000RMXLA, SRT1500XLA, SRT1500RMXLA, SRT1000RMXLA-NC, SRT1500RMXLA-NC:

This revision provides stronger network data security protection via the below mechanisms to prevent malicious firmware from being upgraded to the UPS through communication interface ports (including RJ45).

Change logs:
1. The mechanism of firmware signing adds to the code in order to protect the UPS from malicious firmware spoofs. Based on the above, firmware upgrade via NMC is re-enabled.
2. Addressed battery pack numbering change under certain conditions during UPS firmware upgrade.

Release Notes (UPS 15.1):
========================

SRT1000XLA, SRT1000RMXLA, SRT1500XLA, SRT1500RMXLA, SRT1000RMXLA-NC, SRT1500RMXLA-NC:

1. Addressed 'Miswired' event under certain input conditions.
	
Release Notes (UPS 15.0):
========================

SRT1000XLA, SRT1000RMXLA, SRT1500XLA, SRT1500RMXLA, SRT1000RMXLA-NC, SRT1500RMXLA-NC:

1. Addressed timeout event while receiving the UPS firmware file using NMC under certain conditions. Web link shown below:
	https://www.apc.com/us/en/faqs/index?page=content&id=FA411525 
	
2. This release includes remediations for the security vulnerabilities listed as CVE-2202-0715 which, 
	if compromised, may allow for potential unauthorized access and control of the device.
	Change logs:
		1. Function implemented to disable UPS firmware upgrades via NMC to mitigate potential risk of malicious UPS firmware being passed 
		   through this channel.
		2. Enhanced UPS firmware code protection to mitigate the vulnerabilities of unauthorized extraction of confidential firmware.
		  
Release Notes (UPS 08.2):
========================

SRT1000XLA, SRT1000RMXLA, SRT1500XLA, SRT1500RMXLA, SRT1000RMXLA-NC, SRT1500RMXLA-NC:

1. Addressed erroneous 'Battery Pack Disconnected' and 'Battery Pack Disconnected Cleared' events in the NMC log.
2. Improved algorithm to detect Inverter Hardware Circuit event.
3. Improved capability to detect presence of internal battery in 'battery standby' state.
4. ID is changed from 1019 to 1025 after UPS Firmware Upgrade successfull.

Release Notes (UPS 07.9):
========================

SRT1000XLA, SRT1000RMXLA, SRT1500XLA, SRT1500RMXLA, SRT1000RMXLA-NC, SRT1500RMXLA-NC:

1. Addressed false detection of 'Check Battery Cable' alarm under certain conditions.
2. ID is changed from 1019 to 1025 after UPS Firmware Upgrade successfull.
 




