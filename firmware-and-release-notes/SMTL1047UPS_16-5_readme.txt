Version:  UPS 16.5(SMTL)
Applicable SKUs:
================
ID 1047, All standard SKUs beginning with SMTL prefixes.

SMTL: SMTL1000RM2UC, SMTL1000RMI2U, SMTL1000RMI2UC, SMTL1500RM3UC, SMTL1500RMI3U, SMTL1500RMI3UNC, SMTL2200RM2UC, 
     SMTL2200RM2UCNC, SMTL3000RM2UC, SMTL3000RM2UCNC, SMTL750RM2UC, SMTL750RMI2U, SMTL750RMI2UC, DLTL1500RMI3UC, 
     SMTL1500RMI3UC, SMTL1000RM2UCNC, SMTL1500RM3UCNC, DLTL1500RM3UC, SMTL750RM2UCNC, SMTL2K2R2C-NB, SMTL2K2R2CNC-NB, 
     SMTL3KR2C-NB, SMTL3KR2CNC-NB, SMTL2K2R2CLNC-NB.

This revision revives the communication of the USB port while the UPS is on “suspend” mode when the PCBE starts recommunicating.

Change logs:
1.	Increase the detection of the USB D- signal to escape the “suspended”

Note: Smart-UPS Firmware Upgrade Wizard tool 
always includes the latest released firmware and helps upgrade the UPS code.
Link to tool - https://www.apc.com/us/en/faqs/FA279197/



Previous Released Version:  UPS 16.1(SMTL)
Applicable SKUs:
================
ID 1047, All standard SKUs beginning with SMTL prefixes.

SMTL: SMTL1000RM2UC, SMTL1000RMI2U, SMTL1000RMI2UC, SMTL1500RM3UC, SMTL1500RMI3U, SMTL1500RMI3UNC, SMTL2200RM2UC, 
     SMTL2200RM2UCNC, SMTL3000RM2UC, SMTL3000RM2UCNC, SMTL750RM2UC, SMTL750RMI2U, SMTL750RMI2UC, DLTL1500RMI3UC, 
     SMTL1500RMI3UC, SMTL1000RM2UCNC, SMTL1500RM3UCNC, DLTL1500RM3UC, SMTL750RM2UCNC, SMTL2K2R2C-NB, SMTL2K2R2CNC-NB, 
     SMTL3KR2C-NB, SMTL3KR2CNC-NB, SMTL2K2R2CLNC-NB.

This revision provides stronger network data security protection via the below mechanisms to prevent malicious firmware from being upgraded to the UPS through communication interface ports (including RJ45).

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
AP9631/AP9630 card APP SUMX 6.2.1, AOS 6.2.1
AP9635 CH / AP9631card APP SUMX 6.4.6, AOS 6.4.6
AP9635 CH card APP SUMX 6.4.0, AOS 6.4.0
Power Chute Business Edition v9.2
FUW (Firmware Upgrade Wizard) Tool v4.2.1

