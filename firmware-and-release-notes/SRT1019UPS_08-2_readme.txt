Version:
========
UPS 08.2

Applicable SKUs:
================

SRT1000XLA
SRT1000RMXLA
SRT1500XLA
SRT1500RMXLA
SRT1000RMXLA-NC
SRT1500RMXLA-NC

Compatibility:
==============
FUW Tool version 4.2.0 and above required to upgrade the UPS:
	Web Link for downloading FUW 4.2 Tool and instructions to upgrade the UPS Firmware using FUW - https://www.apc.com/us/en/faqs/index?page=content&id=FA279197	
	UPS with firmware that allows firmware upgrade with output ON:	
		FUW Tool v4.2.1 and above will support firmware upgrade with both output OFF and output ON.
		FUW Tool v4.2.0 and below will support firmware upgrade only with output OFF.	
	Note: The Firmware Upgrade Wizard is the most reliable and preferred method of upgrading. 
	
NMC SUMX v6.5 and above required to upgrade the UPS:
	Web Link for instructions to upgrade the UPS Firmware using NMC - https://www.apc.com/us/en/faqs/index?page=content&id=FA281753	
	UPS with firmware that allows firmware upgrade with output ON:
		NMC v6.5 will support firmware upgrade with both output OFF and output ON.
	Note: if NMC SUMX Version is below 6.5 version, Below Web link helps in upgrading the APC NMC Card with latest NMC SUMX version. 
	      Web Link for instructions to upgrade the firmware on an APC NMC Card - https://www.apc.com/us/en/faqs/index?page=content&id=FA156047  

UPS firmware update compatibility: 
	(a) UPS_07.1 and above versions enables Firmware upgrade process with UPS output ON feature. 	  
	(b) UPS_07.1 and above versions improves firmware upgrade functionality by using stable two step upgrade process.
	(c) UPS_07.1 and above versions supports Auto XBP Firmware upgrade feature under BMC firmware mismatch condition.
	(d) UPS_07.9 and above versions ID will change from 1019 to 1025 after firmware upgrade.
		  
Release Notes (UPS 08.2):
========================

SRT1000XLA, SRT1000RMXLA, SRT1500XLA, SRT1500RMXLA, SRT1000RMXLA-NC, SRT1500RMXLA-NC:

1. Addressed erroneous 'Battery Pack Disconnected' and 'Battery Pack Disconnected Cleared' events in the NMC log.
2. Improved algorithm to detect Inverter Hardware Circuit event.
3. Improved capability to detect presence of internal battery in 'battery standby' state.

Release Notes (UPS 07.9):
========================

SRT1000XLA, SRT1000RMXLA, SRT1500XLA, SRT1500RMXLA, SRT1000RMXLA-NC, SRT1500RMXLA-NC:

1. Addressed false detection of 'Check Battery Cable' alarm under certain conditions.
 




