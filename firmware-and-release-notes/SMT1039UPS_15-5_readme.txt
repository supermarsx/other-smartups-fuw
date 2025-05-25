Version:  UPS 15.5(SMT)
Applicable SKUs:
================
ID 1039, All standard SKUs beginning with SMT prefixes.

SMT: SMT2200R2X167

This revision revives the communication of the USB port while the UPS is on “suspend” mode when the PCBE starts recommunicating.

Change logs:
1.	Increase the detection of the USB D- signal to escape the “suspended”

Note: Smart-UPS Firmware Upgrade Wizard tool 
always includes the latest released firmware and helps upgrade the UPS code.
Link to tool - https://www.apc.com/us/en/faqs/FA279197/



Previous Released Version:  UPS 15.1(SMT)
Applicable SKUs:
================
ID 1039, All standard SKUs beginning with SMT prefixes.

SMT: SMT2200R2X167

This revision provides stronger network data security protection via the below mechanisms to prevent malicious firmware from being upgraded to the UPS through communication interface ports (including RJ45).

Change logs:
1.The mechanism of firmware signing adds to the code in order to protect the UPS from malicious firmware spoofs.

Note: Smart-UPS Firmware Upgrade Wizard tool 
always includes the latest released firmware and helps upgrade the UPS code via serial(RS232) port; Upgrade via USB port from this tool is not recommended.
Link to tool - https://www.apc.com/us/en/faqs/FA279197/



Previous Released Version:
========
UPS 15.0

Applicable Models:
==================
Smart-UPS Online SMT UPSs rated 750VA/2200VA and ID 1039 


Compatibility:
==============
PCBE 9.2
NMC SUMX 6.2.1


Release Notes (UPS15.0):
========================
1.Add FileTransferSourceSetting(Firmware Update Interfaces) in display.
2.Menu in Advanced Mode: Main Menu Configuration -> Firmware Update Interfaces -> Serial/USB/SmartSlot port enable/disable setting.
3.Enhanced code protection for the processor to defend against the possibility of an external intrusion.
