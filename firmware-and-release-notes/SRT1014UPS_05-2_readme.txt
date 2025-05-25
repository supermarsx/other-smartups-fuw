Version:
========
UPS 05.2


Applicable SKUs:
================

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
	Web Link for downloading FUW 4.2 Tool and instructions to upgrade the UPS Firmware using FUW - https://www.apc.com/us/en/faqs/index?page=content&id=FA279197	
	Note: The Firmware Upgrade Wizard is the most reliable and preferred method of upgrading. 
	
NMC SUMX v6.5 and above required to upgrade the UPS:
	Web Link for instructions to upgrade the UPS Firmware using NMC - https://www.apc.com/us/en/faqs/index?page=content&id=FA281753		
	Note: if NMC SUMX Version is below 6.5 version, Below Web link helps in upgrading the APC NMC Card with latest NMC SUMX version. 
		  Web Link for instructions to upgrade the firmware on an APC NMC Card - https://www.apc.com/us/en/faqs/index?page=content&id=FA156047

UPS firmware update compatibility:		  
    (a) UPS 05.1 and above versions supports Auto XBP Firmware upgrade feature under BMC firmware mismatch condition.
	Note: UPS ID 1014 will not support firmware upgrade with UPS output ON feature amd two step firmware upgrade process. 

Release Notes (UPS 05.2):
=========================

SRT8KXLI, SRT8KXLT, SRT8KXLT-IEC , SRT8KRMXLI, SRT8KRMXLT, SRT8KRMXLT-IEC, SRT10KXLI, SRT10KXLT, SRT10KXLT-IEC, SRT10KRMXLI, SRT10KRMXLT, SRT10KRMXLT-IEC,
SRT10RMXLIX806, SRT10KXLTTW, DLRT8KRMXLI, DLRT8KRMXLT:
 
1. Addressed erroneous 'Battery Pack Disconnected' and 'Battery Pack Disconnected Cleared' events in the NMC log.
2. Improved system behavior to eliminate false triggering of Output distorted event.
3. Improved algorithm to detect Inverter Hardware Circuit event.
4. Improved algorithm to detect Back feed Relay weld event.
5. Improved capability to detect presence of internal battery in 'battery standby' state. 

Release Notes (UPS 05.1):
========================

SRT8KXLI, SRT8KXLT, SRT8KXLT-IEC , SRT8KRMXLI, SRT8KRMXLT, SRT8KRMXLT-IEC, SRT10KXLI, SRT10KXLT, SRT10KXLT-IEC, SRT10KRMXLI, SRT10KRMXLT, SRT10KRMXLT-IEC,
SRT10RMXLIX806, SRT10KXLTTW, DLRT8KRMXLI, DLRT8KRMXLT:

1. Improved system handling of over temperature conditions.
2. Changed wording for certain LCD status/warning messages.

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


