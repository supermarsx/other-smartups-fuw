Version:
========
UPS 15.6

Applicable Models:
==================

SRT1000UXI-LI
SRT1000UXI-NCLI
SRT1500UXI-LI
SRT1500UXI-NCLI
SRT2200UXI-LI
SRT2200UXI-NCLI
SRT3000UXI-LI
SRT3000UXI-NCLI 

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
	(a) UPS_00.4 and above versions enables Firmware upgrade process with UPS output ON feature. 	  
	(b) UPS_00.3 and above versions improves firmware upgrade functionality by using stable two step upgrade process.
	(c) UPS_00.3 and above versions supports Auto XBP Firmware upgrade feature under BMC firmware mismatch condition.
	
Note:
=====
Web Link for causes for Smart-UPS firmware upgrade to timeout - https://www.apc.com/us/en/faqs/FA410710/

Release Notes (UPS 15.6):
========================
SRT1000UXI-LI, SRT1000UXI-NCLI, SRT1500UXI-LI, SRT1500UXI-NCLI, SRT2200UXI-LI, SRT2200UXI-NCLI, SRT3000UXI-LI, SRT3000UXI-NCLI,
SRT1000UXI-LI, SRT1000UXI-NCLI, SRT1500UXI-LI, SRT1500UXI-NCLI:

1. Improved the reliability of the firmware upgrade process under certain conditions : "Comm Event: To Pwr Off" and repeated firmware installations.
2. Addressed battery charger event triggered through control firmware under certain conditions.

Release Notes (UPS 15.5):
========================
SRT1000UXI-LI, SRT1000UXI-NCLI, SRT1500UXI-LI, SRT1500UXI-NCLI, SRT2200UXI-LI, SRT2200UXI-NCLI, SRT3000UXI-LI, SRT3000UXI-NCLI,
SRT1000UXI-LI, SRT1000UXI-NCLI, SRT1500UXI-LI, SRT1500UXI-NCLI:

This revision provides stronger network data security protection via the below mechanisms to prevent malicious firmware from being upgraded to the UPS through communication interface ports (including RJ45).

Change logs:
1. The mechanism of firmware signing adds to the code in order to protect the UPS from malicious firmware spoofs. Based on the above, firmware upgrade via NMC is re-enabled.
2. Addressed battery pack numbering change under certain conditions during UPS firmware upgrade.

Release Notes (UPS 15.3):
========================
SRT1000UXI-LI, SRT1000UXI-NCLI, SRT1500UXI-LI, SRT1500UXI-NCLI, SRT2200UXI-LI, SRT2200UXI-NCLI, SRT3000UXI-LI, SRT3000UXI-NCLI,
SRT1000UXI-LI, SRT1000UXI-NCLI, SRT1500UXI-LI, SRT1500UXI-NCLI:

1. Addressed battery general event under certain conditions during UPS firmware upgrade with 50AH Battery Pack XBP48RM2U-LI. 

Release Notes (UPS 15.2):
========================
SRT1000UXI-LI, SRT1000UXI-NCLI, SRT1500UXI-LI, SRT1500UXI-NCLI, SRT2200UXI-LI, SRT2200UXI-NCLI, SRT3000UXI-LI, SRT3000UXI-NCLI,
SRT1000UXI-LI, SRT1000UXI-NCLI, SRT1500UXI-LI, SRT1500UXI-NCLI:

1. Addressed 'Miswired' event under certain input conditions.
2. Made UPS firmware compatible with 50AH Battery Pack XBP48RM2U-LI. 
	
Release Notes (UPS 15.0):
========================
SRT1000UXI-LI, SRT1000UXI-NCLI, SRT1500UXI-LI, SRT1500UXI-NCLI, SRT2200UXI-LI, SRT2200UXI-NCLI, SRT3000UXI-LI, SRT3000UXI-NCLI,
SRT1000UXI-LI, SRT1000UXI-NCLI, SRT1500UXI-LI, SRT1500UXI-NCLI:

1. Addressed timeout event while receiving the UPS firmware file using NMC under certain conditions. Web link shown below:
	https://www.apc.com/us/en/faqs/index?page=content&id=FA411525 
	
2. This release includes remediations for the security vulnerabilities listed as CVE-2202-0715 which, 
	if compromised, may allow for potential unauthorized access and control of the device.
	Change logs:
		1. Function implemented to disable UPS firmware upgrades via NMC to mitigate potential risk of malicious UPS firmware being passed 
		   through this channel.
		2. Enhanced UPS firmware code protection to mitigate the vulnerabilities of unauthorized extraction of confidential firmware.
	
Release Notes (UPS 01.0):
========================
SRT1000UXI-LI, SRT1000UXI-NCLI, SRT1500UXI-LI, SRT1500UXI-NCLI, SRT2200UXI-LI, SRT2200UXI-NCLI, SRT3000UXI-LI, SRT3000UXI-NCLI,
SRT1000UXI-LI, SRT1000UXI-NCLI, SRT1500UXI-LI, SRT1500UXI-NCLI:

1. Improved Battery Pack identification through the LCD Display in About->Battery menu.

	
Release Notes (UPSa00.9):
========================
SRT1000UXI-LI, SRT1000UXI-NCLI, SRT1500UXI-LI, SRT1500UXI-NCLI, SRT2200UXI-LI, SRT2200UXI-NCLI, SRT3000UXI-LI, SRT3000UXI-NCLI,
SRT1000UXI-LI, SRT1000UXI-NCLI, SRT1500UXI-LI, SRT1500UXI-NCLI:

1. Improved Runtime prediction provided by the UPS.

Release Notes (UPS 00.8):
========================

SRT1000UXI-LI, SRT1000UXI-NCLI, SRT1500UXI-LI, SRT1500UXI-NCLI, SRT2200UXI-LI, SRT2200UXI-NCLI, SRT3000UXI-LI, SRT3000UXI-NCLI:
1. Addressed erroneous 'Battery Pack Disconnected' and 'Battery Pack Disconnected Cleared' events in the NMC log.
2. Improved algorithm to detect Inverter Hardware Circuit event.
3. Improved capability to detect presence of internal battery in 'battery standby' state.
4. Addressed false detection of 'Check Battery Cable' alarm under certain conditions.

SRT1000UXI-LI, SRT1000UXI-NCLI, SRT1500UXI-LI, SRT1500UXI-NCLI:
1. Addressed 'new battery installation' message on display after firmware upgrade. 









