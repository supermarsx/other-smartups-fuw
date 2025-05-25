Version:
========
UPS 08.3

Applicable SKUs:
================

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
	(a) UPS_07.9 and above versions enables Firmware upgrade process with UPS output ON feature. 	  
	(b) UPS_07.9 and above versions improves firmware upgrade functionality by using stable two step upgrade process.
	(c) UPS_06.0 and above versions supports Auto XBP Firmware upgrade feature under BMC firmware mismatch condition.
    (d) UPS_07.9 and above versions ID will change from 1010 to 1025 after firmware upgrade.	
	  
Release Notes (UPS 08.3):
========================

SRT2200XLI, SRT2200RMXLI, SRT2200RMXLI-NC, SRT3000XLI, SRT3000RMXLI, SRT3000RMXLI-NC, SRT3000XLT,
SRT3000RMXLT, SRT3000RMXLT-NC, SRT3000XLW-IEC, SRT3000RMXLW-IEC, DLRT3000RMXLI: 

SRT2200XLA, SRT2200RMXLA, SRT3000XLA, SRT3000RMXLA, SRT2200RMXLA-NC, SRT3000RMXLA-NC,
SRT3000XLA-TW, DLRT3000RMXLA:

1. Improved sub-system version compatibility for SRT1010UPS_08.2.enc File. There is No change in system performance. 


Release Notes (UPS 08.2):
========================

SRT2200XLI, SRT2200RMXLI, SRT2200RMXLI-NC, SRT3000XLI, SRT3000RMXLI, SRT3000RMXLI-NC, SRT3000XLT,
SRT3000RMXLT, SRT3000RMXLT-NC, SRT3000XLW-IEC, SRT3000RMXLW-IEC, DLRT3000RMXLI: 

SRT2200XLA, SRT2200RMXLA, SRT3000XLA, SRT3000RMXLA, SRT2200RMXLA-NC, SRT3000RMXLA-NC,
SRT3000XLA-TW, DLRT3000RMXLA:

1. Addressed erroneous 'Battery Pack Disconnected' and 'Battery Pack Disconnected Cleared' events in the NMC log.
2. Improved algorithm to detect Inverter Hardware Circuit event.
3. Improved capability to detect presence of internal battery in 'battery standby' state.

Release Notes (UPS 07.9):
========================

SRT2200XLI, SRT2200RMXLI, SRT2200RMXLI-NC, SRT3000XLI, SRT3000RMXLI, SRT3000RMXLI-NC, SRT3000XLT,
SRT3000RMXLT, SRT3000RMXLT-NC, SRT3000XLW-IEC, SRT3000RMXLW-IEC, DLRT3000RMXLI:

1. Improved system handling of over temperature conditions.
2. Changed wording for certain LCD status/warning messages.
3. Addressed false detection of 'Check Battery Cable' alarm under certain conditions.

SRT2200XLA, SRT2200RMXLA, SRT3000XLA, SRT3000RMXLA, SRT2200RMXLA-NC, SRT3000RMXLA-NC,
SRT3000XLA-TW, DLRT3000RMXLA:

1. Improved system handling of over temperature conditions.
2. Changed wording for certain LCD status/warning messages.
3. Addressed false detection of 'Check Battery Cable' alarm under certain conditions.







