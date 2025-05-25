Version:
========
UPS 15.1


Applicable Models:
==================
XP1K9NN42RCC


Compatibility:
==============
FUW Tool version 4.2.0 and above required to upgrade the UPS:
	Web Link for downloading FUW 4.3.0 Tool and instructions to upgrade the UPS Firmware using FUW - https://www.apc.com/us/en/faqs/index?page=content&id=FA279197	
	UPS with firmware that allows firmware upgrade with output ON:	
		FUW Tool v4.2.1 and above will support firmware upgrade with both output OFF and output ON.
		FUW Tool v4.2.0 and below will support firmware upgrade only with output OFF.	
	Note: The Firmware Upgrade Wizard is the most reliable and preferred method of upgrading. 
	
NMC SUMX v6.5 and above required to upgrade the UPS:
	Web Link for instructions to upgrade the UPS Firmware using NMC - https://www.apc.com/us/en/faqs/FA170679/	
	UPS with firmware that allows firmware upgrade with output ON:
		NMC v6.5 will support firmware upgrade with both output OFF and output ON.
	Note: if NMC SUMX Version is below 6.5 version, Below Web link helps in upgrading the APC NMC Card with latest NMC SUMX version. 
		  Web Link for instructions to upgrade the firmware on an APC NMC Card - https://www.apc.com/us/en/faqs/index?page=content&id=FA156047
		  
Release Notes (UPS 15.1):
========================
1. Improved the reliability of the firmware upgrade process under certain condition : "Comm Event: To Pwr Off". 
		  
Release Notes (UPS 15.0):
========================
1. This release includes remediations for the security vulnerabilities listed as CVE-2202-0715 which, 
	if compromised, may allow for potential unauthorized access and control of the device.
	Change logs:
		1. Function implemented to disable UPS firmware upgrades via NMC to mitigate potential risk of malicious UPS firmware being passed 
		   through this channel.
		2. Enhanced UPS firmware code protection to mitigate the vulnerabilities of unauthorized extraction of confidential firmware.


Release Notes (UPS 02.3):
========================
1. Added support for USB mass storage devices to save logs, import and save config.ini files, and download firmware
updates.
2. Improved system handling of issues during a firmware update.
3. Improved system logging behavior for certain conditions.
4. Improved system handling of DC bus delta alarm under certain conditions.
5. Improved system behavior during a runtime calibraion.
6. Improved system behavior of relay icons on LCD home screen.