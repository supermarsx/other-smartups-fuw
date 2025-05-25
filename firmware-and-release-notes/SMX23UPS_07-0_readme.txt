Version:
========
UPS 07.0


Previous Released Version:
==========================
UPS 06.9


Applicable SKUs:
================
FJX3000RMLV2U
FJX3000RMHV2UNC
HTX3000RMLV2U
NMX3000RMLV2U
SMX2000RMLV2U
SMX2000RMLV2UNC
SMX2200RMHV2U
SMX2200RMLV2U
SMX3000RMHV2U
SMX3000RMHV2UNC
SMX3000RMJ2U
SMX3000RMLV2U
SMX3000RMLV2UNC
DLX3000RMLVJ2U
HTX3000RMHV2U


Compatibility:
==============
PCBE 9.1.1
NMC SUMX 6.2.0


Release Notes (UPS 07.0):
=========================
1. Adjusted sensitivity in Fair and Poor Input Power Quality settings.


Release Notes (UPS 06.9):
=========================
1. Fixed issue which in rare cases prevented the UPS from powering on with good AC input and good battery voltage.


Release Notes (UPS 06.8):
=========================
1. Updates to the LCD menu translations for improved clarity.
2. Improved communication noise immunity and reliability.
3. Improved reliability and performance of system configurations with an Interface Expander 2 card and communicating with PCBE.
4. Added feature to allow for locking the UI display menus from external clients, such as PCBE and NMC.


Release Notes (UPS 06.6):
=========================
1. Adds compatibility with Interface Expander 2 (AP9624) accessory card.
2. Addresses issue where the start time of a scheduled Self-Test is shifted from expected. Improved the repeatability of the scheduled self-test timer.
3. Increased upper end of allowed limits for Minimum Return Runtime, Load Shed Runtime Remaining, and Low Runtime Warning to match other Smart-UPS.
4. Simplified display of the firmware version on LCD, removing unnecessary information.
5. Moved NMC information from advanced menus to standard menu on LCD.
6. Improved the configuration of the NMC via the LCD.
7. Improved the reporting of efficiency on display to indicate reason for low efficiency


Release Notes (UPS 06.5):
=========================
1. Improve the reliability and behavior of system during a Self-Test.


Release Notes (UPS 06.4):
=========================
1. Fixes various issues which could lead to a long transfer.
2. Fixes issue which could sometimes cause a false detection of a backfeed relay fault.
3. Removed other posential issues, to increase robustness of code.

Release Notes (UPS 06.2):
=========================
1. Fixes issue where Self Test could run for a prolonged period of time.
2. Fixes issue where UPS could indicate Inverter low voltage during recovery from shutdown

Release Notes (UPS 06.1):
=========================
1. Fixes issue where following reset to factory defaults, the Power Quality setting shows up with
incorrect default value.
2. Fixes issue where software could set an invalid value for Sensitivity setting.

Release Notes (UPS 06.0):
=========================
1. Updates to the LCD menu translations for improved clarity.
