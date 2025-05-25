Version: UPS 06.8
Applicable Models:
==================
ID 1035 with SmartConnect SKU.
SRTL3KRM1UC, SRTL2K2RM1UC

Change logs:
	1. Improve DC/DC discharging control algorithm for light load condition.
	2. Optimize fan speed control for light load condition.
	3. Improve UPS behavior when inverter shorts into AC mains.
	4. Enhance UPS power-off mechanism in stand-by mode without AC utility to prevent battery drain.
	5. Improve charger control algorithm to keep charger working when multiple battery packs are connected, and some batteries
	   exhibit protected behavior.
	6. If AC utility is unexpectedly turned off during firmware upgrade with output on process, ensure UPS output is
	   automatically turned on after firmware upgrade and AC utility recovered.
	7. Improve output auto-restart function after waking up from UPS shutdown.
	8. Improve self-test function when battery pack protection is abnormally triggered during the test.


Version: UPS 06.7
Applicable Models:
==================
ID 1035 with SmartConnect SKU.
SRTL3KRM1UC, SRTL2K2RM1UC

Change logs:
	1. Improve charger control by revising charger turn on sequence to minimize interference between 2-stage DC-DC converters.
	2. Improve charger control by limiting maximum charging current compensation.
	3. Improve charger control by turning off pre-charge subsystem after charger is on.
	4. Improve robustness for bypass to on-line and bypass to on-battery transfers.
	5. Add a protection mechanism for battery fuse open. 
	6. Improve firmware upgrade progress to have continuous percentage indication on LCD panel.
	7. Log continuous "Incompatible battery pack" event only once instead of multiple times.


Version: UPS 06.3
Applicable Models:
==================
ID 1035 with SmartConnect SKU.
SRTL3KRM1UC, SRTL2K2RM1UC

Change logs:
	1. Enhance back-feed relay weld detection to resolve P.05 issue when UPS transits to on-battery state and input voltage is
	   floating.
	2. Improve charger control for solving charger B.04 issue.
	3. If XBP ID is not correctly set, UPS will report it as an alarm with continuous beep and LCD panel background in red
	   color.
	4. Correctly display battery manufacture and installation date information on the LCD.


Version: UPS 06.1
Applicable Models:
==================
ID 1035 with SmartConnect SKU.
SRTL3KRM1UC, SRTL2K2RM1UC

Change logs:
	1. Improve firmware upgrading skip function to speed up upgrading time.
	2. Enhance firmware upgrading recovery mechanism to avoid LCD show D.04 after upgraded
	3. Improve frequency sweep sensitivity for generator input.
	4. Keep the UPS output off if UPS abnormal shutdown.
	5. Discreetly report event 186 about charger subsystem.
	6. Improve charger control for solving charger B.04 issue.
	7. Show “Incompatible battery pack” message as an event instead of an alarm
	8. Improve output auto-restart mechanism according to input power status


Version: UPS 05.6
Applicable Models:
==================
ID 1035 with SmartConnect SKU.
SRTL3KRM1UC, SRTL2K2RM1UC

Change logs:
	1. Improved the detection of inter-microprocessor communication to decrease the logs of Event 154.
	2. Improved the firmware upgrade fails via SmartConnect and need to upgrade to this version through FUW.

Version: UPS 05.0
Applicable Models:
==================
ID 1035 with SmartConnect SKU.
SRTL3KRM1UC, SRTL2K2RM1UC

Change logs:
	1. Implement firmware image signature for enhancing cybersecurity.
	2. Reduce firmware upgrade time down to 25 mins.
	2. Improve inter-microprocessor communication quality for D.04 communication alarm.


Version: UPS 04.1
Applicable Models:
==================
ID 1035 with SmartConnect SKU.
SRTL3KRM1UC, SRTL2K2RM1UC

Change logs:
	1. Implement 2.2KVA model(SRTL2K2RM1UC) on this version. The 2.2kVA model should not downgrade before this version.
	2. Improve the charger short circuit function for B.04 charger alarm.
	3. Improve the PFC control for P.12 "Bus Over voltage" alarm while load is removed.
	4. Enhanced UPS firmware code protection to mitigate the vulnerabilities of unauthorized extraction of confidential
	   firmware and un-authorized network access to SmartConnect UPSs.



Version:  UPS 03.2
Applicable SKUs:
================
ID 1035 with SmartConnect SKU.
SRTL3KRM1UC

Change logs:
	1. Initial Released

Compatibility:
==============
PowerChute Business Edition v10.0.2
FUW (Firmware Upgrade Wizard) Tool v4.3.8




