Version:
========
FUW 4.3.8

Previous Released Version:
========
FUW 4.3.7

Applicable Models:
================
APC Smart-UPS SMT, SMX, SMC, SMTL, SRT, SCL, SRTL, SRTXU, XU, XP, CSH ,SRTL series.

OS Compatibility:(64-bit Only)
==============================

Release Notes (FUW 4.3.8):
==========================
1. USB upgrade issue fixed for UPS with the exception of Smart UPS with ID 1013 and 1014.
2. New firmware file updated for SRTL3KRM1UNC/SRTL2K2RM1UNC, SRTL3KRM1UC/SRTL2K2RM1UC, SRTL1062, SRTL1063, SRT1002,SRT1013,SRT1014,SRT1020,SRT1021,SRT1044,SRT1045, SMTL1064,SMC1028,SMT1027,SMC1018,SMT1015.

Known Issues

1. USB upgrade not supported in SMTSMX20 and SMX1003.Please try with Serial Cable that comes with the UPS


Release Notes (FUW 4.3.7):
==========================
1. Support for additional SKU's. Mechanism of firmware signing added to SKU's to re-enable Upgrade from NMC. Refer FirmwareFiles_readme.txt for SKU details.

Known Issue

1. The upgrade Performing a firmware update over the USB port for SKU's sometimes fails. In this case, it is recommended to disconnect the USB cable , to power cycle the UPS by turning the UPS off, disconnecting  the removing battery, disconnecting AC input power, waiting 60 seconds, reconnecting AC power, reconnecting the battery, turning on the UPS, to reconnecting the USB cable and try once again.
   If the upgrade still fails, Please get in touch with the Customer Care Centre.

2. For Smart-UPS XU UPS's, FUW 4.3.4 successfully transfers new firmware file to UPS, however, fails to install the firmware." 
Workaround: After FUW tools has finished transffering, initiate the firmware update via UPS LCD screen.

Release Notes (FUW 4.3.6):
==========================
1. Support for additional SKU's. Mechanism of firmware signing added to SKU's to re-enable Upgrade from NMC. Refer FirmwareFiles_readme.txt for SKU details.

Known Issue

1. The upgrade Performing a firmware update over the USB port for SKU's sometimes fails. In this case, it is recommended to disconnect the USB cable , to power cycle the UPS by turning the UPS off, disconnecting  the removing battery, disconnecting AC input power, waiting 60 seconds, reconnecting AC power, reconnecting the battery, turning on the UPS, to reconnecting the USB cable and try once again.
   If the upgrade still fails, Please get in touch with the Customer Care Centre.

2. For Smart-UPS XU UPS's, FUW 4.3.4 successfully transfers new firmware file to UPS, however, fails to install the firmware." 
Workaround: After FUW tools has finished transffering, initiate the firmware update via UPS LCD screen. 


Release Notes (FUW 4.3.5):
==========================
1. Support for additional SKU's. Mechanism of firmware signing added to SKU's to re-enable Upgrade from NMC. Refer FirmwareFiles_readme.txt for SKU details.

Known Issue

1. The upgrade Performing a firmware update over the USB port for SKU's sometimes fails. In this case, it is recommended to disconnect the USB cable , to power cycle the UPS by turning the UPS off, disconnecting  the removing battery, disconnecting AC input power, waiting 60 seconds, reconnecting AC power, reconnecting the battery, turning on the UPS, to reconnecting the USB cable and try once again.
   If the upgrade still fails, Please get in touch with the Customer Care Centre.

2. For Smart-UPS XU UPS's, FUW 4.3.4 successfully transfers new firmware file to UPS, however, fails to install the firmware." 
Workaround: After FUW tools has finished transffering, initiate the firmware update via UPS LCD screen. 


Release Notes (FUW 4.3.4):
==========================
1. Support for additional SKU's. Mechanism of firmware signing added to SKU's to re-enable Upgrade from NMC. Refer FirmwareFiles_readme.txt for SKU details.

Known Issue

1. The upgrade Performing a firmware update over the USB port for SKU's sometimes fails. In this case, it is recommended to disconnect the USB cable , to power cycle the UPS by turning the UPS off, disconnecting  the removing battery, disconnecting AC input power, waiting 60 seconds, reconnecting AC power, reconnecting the battery, turning on the UPS, to reconnecting the USB cable and try once again.
   If the upgrade still fails, Please get in touch with the Customer Care Centre.

2. For Smart-UPS XU UPS's, FUW 4.3.4 successfully transfers new firmware file to UPS, however, fails to install the firmware." 
Workaround: After FUW tools has finished transffering, initiate the firmware update via UPS LCD screen. 

Release Notes (FUW 4.3.3):
==========================
1. Support for additional SKUs.
2. Update for SRTL Serial Port Upgrade fix.

Known Issue

1. The upgrade Performing a firmware update over the USB port for SKU's sometimes fails. In this case, it is recommended to disconnect the USB cable , to power cycle the UPS by turning the UPS off, disconnecting  the removing battery, disconnecting AC input power, waiting 60 seconds, reconnecting AC power, reconnecting the battery, turning on the UPS, to reconnecting the USB cable and try once again.
   If the upgrade still fails, Please get in touch with the Customer Care Centre.

2. For Smart-UPS XU UPS's, FUW 4.3.3 successfully transfers new firmware file to UPS, however, fails to install the firmware." 
Workaround: After FUW tools has finished transffering, initiate the firmware update via UPS LCD screen. 


Note: While the Wizard allows a downgrade, this is neither recommended nor supported by Schneider Electric, unless directed by a representative of the company.

===================================================
Release Notes (FUW 4.3.2):
==========================
1. Open JDK updated to  17.0.4
2. Support for additional SKUs.
3. log4J version updated to 2.19
4. Access control mechansim added for SKU's. For details refer  https://www.apc.com/us/en/faqs/FAQ000244385/

Known Issue
1. For Smart-UPS SRTL UPS's, FUW 4.3.2 does not support firmware upgrade via serial cable, it is supported only via USB cable.

2. The upgrade Performing a firmware update over the USB port for SKU's sometimes fails. In this case, it is recommended to disconnect the USB cable , to power cycle the UPS by turning the UPS off, disconnecting  the removing battery, disconnecting AC input power, waiting 60 seconds, reconnecting AC power, reconnecting the battery, turning on the UPS, to reconnecting the USB cable and try once again.
   If the upgrade still fails, Please get in touch with the Customer Care Centre.

3.For Smart-UPS XU UPS's, FUW 4.3.2 successfully transfers new firmware file to UPS, however, fails to install the firmware." 
Workaround: After FUW tools has finished transffering, initiate the firmware update via UPS LCD screen. 


Note: While the Wizard allows a downgrade, this is neither recommended nor supported by Schneider Electric, unless directed by a representative of the company.

===================================================

Release Notes (FUW 4.3.1):
==========================
1. Open JDK support 17
2. Support for additional SKUs.

Known Issue
1.For Smart-UPS SRTL UPS's, FUW 4.3.1 does not support firmware upgrade via serial cable, it is supported only via USB cable.

2. The upgrade Performing a firmware update over the USB port for SKU's sometimes fails. In this case, it is recommended to disconnect the USB cable , to power cycle the UPS by turning the UPS off, disconnecting  the removing battery, disconnecting AC input power, waiting 60 seconds, reconnecting AC power, reconnecting the battery, turning on the UPS, to reconnecting the USB cable and try once again.
   If the upgrade still fails, Please get in touch with the Customer Care Centre.

3.For Smart-UPS XU UPS's, FUW 4.3.1 successfully transfers new firmware file to UPS, however, fails to install the firmware." 
Workaround: After FUW tools has finished transffering, initiate the firmware update via UPS LCD screen. 


Note: While the Wizard allows a downgrade, this is neither recommended nor supported by Schneider Electric, unless directed by a representative of the company.


===================================================

Release Notes (FUW 4.3.0):
==========================
1. Open JDK support 16.0.2
2. Increased the number of SKU supported.
3. New implementation that suggests only relevant and latest firmware based on the SKU Number. 
3. Cybersecurity fixes for SMT,SMC SKUs.
4. HASH value included as part of Downloadable executable. Please refer product page on how to check hash value.

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
