Version:
========
FUW 4.2.1


Previous Released Version:
==========================
FUW 4.2.0


Applicable SKUs:
================
Smart-UPS SMT, SMX, SMC, SCL and Smart-UPS On-Line SRT SKUs.

OS Compatibility:
================

Windows 7®, Windows 8.1®, Windows 10®, Windows 2016® and Windows 2019®


Release Notes (FUW 4.2.1):
==========================
1. Introduces Firmware Upgrade with Output ON for the UPS . This is only applicable to UPS that support the feature in hardware and firmware
2. Tracking of Update progress introduced to complete the upgrade wizard as soon as the upgrade completes on UPS.  This is a feature improvement from 
   Customer standpoint.
3. Supports all SKU's that were left unsupported in 4.2.0 release. 

Release Notes (FUW 4.2.0):
==========================

1. Information of Operating System is added to log messages.
2. Removed Progress Bar on Apply Upgrade panel to Rotating Wheels.
3. Improved timings to avoid detecting a Firmware upgrade error screen, although the UPS would have upgraded successfully.
4. Text size changed from primary to secondary font in the ‘Device Firmware Upgrade Ready’ screen to accommodate ‘More Information’ and ‘Release Notes’ tabs. 
5. Code modified to show proper versions of Upgraded Firmware in Finish Screen of FUW tool.


Known Issue: There is an exception with respect to SCL500RM1UC SKU, where FUW tool still displays the old Firmware version, after a successful UPS upgrade. 
Reopening the tool or checking UPS LCD shows the new firmware.


Note: While the Wizard allows a downgrade, this is neither recommended nor supported by Schneider Electric, unless directed by a representative of the company.


Release Notes (FUW 4.1.2):
==========================

1. Dynamic handling of FileTransferToMasterStatus_BF to cater for different sizes 2 and 4 bytes

Release Notes (FUW 4.1.1):
==========================

1. Enhanced USB reliability by improving the performance of the listening loops. Addressed missing USB packet issue observed with SRT UPS models and 
certain Windows operating systems.
2. Added USB support for SRT models on Windows 8.0®, 8.1® and Windows 10®.


Release Notes (FUW 4.1):
========================
1. Added support for Legacy Communication Cards.
2. Added support for Cloud enabled SmartSlot Cards.
3. Updated bundled JRE to 1.8.0_60.
4. Added recovery method for SRT UPS models when in an invalid state.


Release Notes (FUW 4.0):
========================
1. Added support for SRT UPS models.
2. Added the ability to display a revision note if available.
3. Added encryption of log files.
4. Bundled FUW with its own 32-bit JRE environment.
5. Improved upgrade speed by adding ability to install only applications required by the UPS.
6. Improved timing for the UPS detection, reducing the risk of failing USB connections.
7. Improved the stability of USB connections.
