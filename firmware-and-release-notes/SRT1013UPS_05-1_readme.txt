Version:
========
UPS 05.1


Applicable SKUs:
================
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
	Web Link for downloading FUW 4.2 Tool and instructions to upgrade the UPS Firmware using FUW - https://www.apc.com/us/en/faqs/index?page=content&id=FA279197
	Note: The Firmware Upgrade Wizard is the most reliable and preferred method of upgrading. 
	
NMC SUMX v6.5 and above required to upgrade the UPS:
	Web Link for instructions to upgrade the UPS Firmware using NMC - https://www.apc.com/us/en/faqs/index?page=content&id=FA281753	
	Note: if NMC SUMX Version is below 6.5 version, Below Web link helps in upgrading the APC NMC Card with latest NMC SUMX version. 
		  Web Link for instructions to upgrade the firmware on an APC NMC Card - https://www.apc.com/us/en/faqs/index?page=content&id=FA156047

UPS firmware update compatibility:		  
    (a) UPS 04.5 and above versions supports Auto XBP Firmware upgrade feature under BMC firmware mismatch condition.
	Note: UPS ID 1013 will not support firmware upgrade with UPS output ON feature amd two step firmware upgrade process. 

Release Notes (UPS 05.1):
=========================
 
SRT5KXLI, SRT5KXLT, SRT5KXLT-IEC, SRT5KRMXLI, SRT5KRMXLT, SRT5KRMXLT-IEC, SRT6KXLI, SRT6KXLT, SRT6KXLT-IEC, SRT6KRMXLI, SRT6KRMXLT, SRT6KRMXLT-IEC, 
SRT5KRMXLW-TW, SRT5KRMXLW-HW, SMRT5KRMXLW-HW, SRT6KXLTW, DLRT5KRMXLI, DLRT5KRMXLT, SRT5KRMXLIM, SRT6KRMXLIM, FJRT5KXLI:

1. Addressed erroneous 'Battery Pack Disconnected' and 'Battery Pack Disconnected Cleared' events in the NMC log.
2. Improved algorithm to detect Inverter Hardware Circuit event.
3. Improved capability to detect presence of internal battery in 'battery standby' state.

SRT5KXLJ, DLRT5KRMXLJ, HTRT5KRMXLJ, FJRT5KRMXLJ, NCRT5KRMXLJ:

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
  


