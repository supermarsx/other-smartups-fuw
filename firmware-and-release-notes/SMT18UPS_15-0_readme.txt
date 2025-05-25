Version:
========
UPS 15.0

Previous Released Version:
==========================
UPS 09.8

Applicable Models:
==================
Smart-UPS SMT UPSs (except 1U) rated 0.75, 1 & 1.5 kVA with ID 18 


Compatibility:
==============
PCBE 9.2
NMC SUMX 6.2.1

Release Notes (UPS15.0):
========================
1.Add FileTransferSourceSetting(Firmware Update Interfaces) in display.
2.Menu in Advanced Mode: Main Menu Configuration -> Firmware Update Interfaces -> Serial/USB/SmartSlot port enable/disable setting. 
3.Refer here for details on UPS access control mechanism https://www.apc.com/us/en/faqs/FAQ000244385/ 

Release Notes (UPS09.8):
========================
1. Resolves scheduled self-test failed issue.


Release Notes (UPS09.6):
========================
1. Fixed an incorrect calculation of the Replace Battery date which occurred when the NMC was installed.



Release Notes (UPS09.5):
========================
1. Improved consistency of the UPS transfer time stamp between the NMC event log and UPS transfer log.
2. Improved the ability of the UPS to support the load during self-test if the battery is bad.



Release Notes (UPS09.4):
========================
1.  SmartSlot card information displayed on the LCD is cleared when new card is hot-swapped 
2.  Updated LCD message in Japanese when canceling sleep.
3.  Improved robustness of serial port communications to avoid errant serial port characters from causing delayed UPS operations.
4.  LCD display operation with Legacy Communication Card (AP9620) improved to eliminate LCD display of items that are inaccessible when AP9620 is used.
5.  Improved reliability of native USB operation command DelayBeforeShutdown and switched outlet control.  
    This improves compatibility with Custom software applications, and native OS shutdown agents.
6.  Improved the cancelling of a UPS output programmed-off duration (sleep).
7.  Improved programmed-off duration (sleep) response to power outage.

