Version:
========
UPS 15.0


Previous Released Version:
==========================
UPS 10.2


Applicable SKUs:
================
DLT1200RMJ1U
FJM1200RMJ1U
FJX1500RMI2UNC
HTM1200RMJ1U
NMM1200RMJ1U
NMM1200RMJ1UB
SMT1200RMJ1U
SMT1500RM1U
SMT1500RMI1U
SMX1000
SMX1000I
SMX1500RM2U
SMX1500RM2UNC
SMX1500RMI2U
SMX1500RMI2UNC
SMX750
SMX750I


Compatibility:
==============
PCBE 9.1.1
NMC SUMX 6.5.0

Release Notes (UPS15.0):
========================
1.Add FileTransferSourceSetting(Firmware Update Interfaces) in display.
2.Menu in Advanced Mode: Main Menu Configuration -> Firmware Update Interfaces -> Serial/USB/SmartSlot port enable/disable setting. 
3.Refer here for details on UPS access control mechanism https://www.apc.com/us/en/faqs/FAQ000244385/ 

Release Notes (UPS 10.2):
==============
1. Resolves SMX750 & SMX750I communication issue in UPS 10.1.


Release Notes (UPS 10.1):
==============
1. Added support for Modbus RTU communication over USB/Serial. See APC Application Note #176 for more details.


Release Notes (UPS 09.9):
==============
1. Improved UPS handling of very weak batteries.
2. Improved replace battery indicator condition.
3. Adjusted fan turn on/off criteria.
4. Corrected Japanese translation for "Cancelled".


Release Notes (UPS 09.8):
==============
1. Adds compatibility with Interface Expander 2 (AP9624) accessory card.
2. Addresses issue where the start time of a scheduled Self-Test is shifted from expected.
3. Increased upper end of allowed limits for Minimum Return Runtime, Load Shed Runtime Remaining, and Low Runtime Warning to match other Smart-UPS.
4. Simplified display of the firmware version on LCD.


Release Notes (UPS 09.7):
==============
1. Addresses issue where updating from v9.2->v9.6 would erase serial number.
2. Addresses issue where battery lifetime timer was running about 1.7% slower than real time.
3. Addresses issue where manual self-test command will rarely be refused and result in a false momentary disconnected battery condition.
4. Addresses issue where self tests will occasionally remain in pending state for several minutes to several hours before executing.


Release Notes (UPS 09.6):
==============
1. Addresses issue where repeated Shutdown/Wakeup cycles would occasionally yield a self-test on Wakeup.
2. Addresses issue where under some rare conditions unit would not Wakeup from Sleep.
3. Addresses issue where in Normal sensitivity setting unit would not reliably turn On from Standby with distorted input.


Release Notes (UPS 09.5):
==============
1. Fix some menu translations.
2. Added some LCD indications when Run Time Calibration is prohibited.
3. Added NMC information into LCD basic mode screen.
4. Overtemperature fault should sound audible alarm.
5. Minor changes in beeping of unit to match other Smart-UPS 5G products.
6. Enhancements to replace battery by date to improve interoperability with NMC and PCBE.
7. Fix USB-HID usage "DelayBeforeReboot".
8. Updated USB HID usage Present Status to indicate ShutdownRequested whenever a shutdown is in progress.
9. Corrected Simple Signaling timing to always have LineFail Pin asserted when output is off, removed glitch in ShutdownImminent at turn on.
10. Improved the configuration of the NMC via the LCD.
11. Setup Wizard will not time out on initial setup, but will timeout on reset to factory defaults. Setup wizard will include a splash screen.
12. Added logic to prevent toggling from line high -> battery at very high input voltage.
13. Increased the reportable runtime remaining capability beyond 18.2 hours.
14. Improve response times for blackouts under Fair Power Quality Setting.


Release Notes (UPS 09.2):
==============
1. Added improved bootloader to protect against malicious attacks
2. Improved the fault log display of errors.
3. Changed the default value for LowRuntimeWarning to 150s
4. Improved the efficiency display to indicate reason for low efficiency
