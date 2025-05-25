Version:  UPS 16.5
Applicable SKUs:
================
ID 1050, All standard SKUs beginning with SMT/SMX prefixes.
SMX: SMX750C, SMX750CNC, SMX1000C, SMX1000CNC, SMX1500RM2UC, SMX1500RM2UCNC
SMT: SMT1500RM1UC, SMT1200RMJ1U


This revision provides stronger network data security protection via the below mechanisms to prevent malicious firmware from being upgraded to the UPS through communication interface ports.

Change logs:
1. The mechanism of firmware signing adds to the code in order to protect the UPS from malicious firmware spoofs. Based on the above, firmware upgrade via NMC is re-enabled. 
2. Added the selection of "FW Update Interfaces" under the LCD Menu->Configuration. This can assist the user to decide whether or not firmware upgrades are allowed through designated communication ports.
3. Changed TLS used for SmartConnect to MbedTLS for cybersecurity.

Note: Smart-UPS Firmware Upgrade Wizard tool 
always includes the latest released firmware and helps upgrade the UPS code via serial(RS232) port; Upgrade via USB port from this tool is not recommended.
Link to tool - https://www.apc.com/us/en/faqs/FA279197/



Initial Released Version: UPS 16.0


Compatibility:
==============
AP9613 Dry Contact Version Next Gen Relay IO card 2.1
AP9620 LCC Version 3.0
AP9624 (Second Gen Interface Expander Card) v1.0X
AP9631/AP9630 card APP SUMX 6.9.6, AOS 6.9.6
AP9635 CH card APP SUMX 6.9.6, AOS 6.9.6
AP9640/AP9641/AP9643 – su v1.4.2.1, aos v1.4.2.1, boot v1.1.0.2
PowerChute Business Edition v10.0.2
FUW (Firmware Upgrade Wizard) Tool v4.2.1