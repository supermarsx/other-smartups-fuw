Version:  UPS 17.2(SMT)
Applicable SKUs:
================
ID 1027, All standard SKUs beginning with SMT prefixes.

SMT: SMT750C, SMT750RM2UC, SMT1000C, SMT1000RM2UC, SMT1500C, SMT1500RM2UC, SMT2200C,     
SMT2200RM2UC, SMT3000C, SMT3000RM2UC, SMT750IC, SMT750RMI2UC, SMT1000IC, SMT1000RMI2UC, SMT1500IC, SMT1500RMI2UC, SMT2200IC, SMT2200RMI2UC, SMT3000IC, SMT3000RMI2UC
 
Change logs
1.	Fixed an indication issue that EnergyHour stopped counting up.


Note: The Smart -UPS Firmware Upgrade Wizard tool always includes the latest firmware and helps you to upgrade to the UPS. For more information on the tool, see FA279197.



Version:  UPS 17.2(SMT)
Applicable SKUs:
================
ID 1027, All standard SKUs beginning with SMT prefixes.

SMT: SMT750C, SMT750RM2UC, SMT1000C, SMT1000RM2UC, SMT1500C, SMT1500RM2UC, SMT2200C,     
SMT2200RM2UC, SMT3000C, SMT3000RM2UC, SMT750IC, SMT750RMI2UC, SMT1000IC, SMT1000RMI2UC, SMT1500IC, SMT1500RMI2UC, SMT2200IC, SMT200RMI2UC, SMT3000IC, SMT3000RMI2UC
 
Change logs
1.	Added a patch code for the affected SKUs as below to fix the RBC indication on the LCD panel with the correct RBC string, affected SKUS SMT3000IC, SMT3000C, SMT2200RMI2UC and SMT2200RM2UC.


Note: The Smart -UPS Firmware Upgrade Wizard tool always includes the latest firmware and helps you to upgrade to the UPS. For more information on the tool, see FA279197.



Version:  UPS 17.0(SMT)
Applicable SKUs:
================
ID 1027, All standard SKUs beginning with SMT prefixes.

SMT: SMT750C, SMT750RM2UC, SMT1000C, SMT1000RM2UC, SMT1500C, SMT1500RM2UC, SMT2200C,     
SMT2200RM2UC, SMT3000C, SMT3000RM2UC, SMT750IC, SMT750RMI2UC, SMT1000IC, SMT1000RMI2UC, SMT1500IC, SMT1500RMI2UC, SMT2200IC, SMT2200RMI2UC, SMT3000IC, SMT3000RMI2UC

This revision revives the communication of the USB port while the UPS is on “suspend” mode when the PCBE starts recommunicating.


Change logs:
1.	Increase the detection of the USB D- signal to escape the “suspended”


Note: Smart-UPS Firmware Upgrade Wizard tool 
always includes the latest released firmware and helps upgrade the UPS code.
Link to tool - https://www.apc.com/us/en/faqs/FA279197/



Version:  UPS 16.5(SMT)
Applicable SKUs:
================
ID 1027, All standard SKUs beginning with SMT prefixes.

SMT: SMT750C, SMT750RM2UC, SMT1000C, SMT1000RM2UC, SMT1500C, SMT1500RM2UC, SMT2200C,     
SMT2200RM2UC, SMT3000C, SMT3000RM2UC, SMT750IC, SMT750RMI2UC, SMT1000IC, SMT1000RMI2UC, SMT1500IC, SMT1500RMI2UC, SMT2200IC, SMT2200RMI2UC, SMT3000IC, SMT3000RMI2UC

This revision provides stronger network data security protection via the below mechanisms to prevent malicious firmware from being upgraded to the UPS through communication interface ports (including RJ45).

Change logs:
1.	The mechanism of firmware signing adds to the code in order to protect the UPS from malicious firmware spoofs. Based on the above, firmware upgrade via NMC is re-enabled. 
2.	Added the selection of "FW Update Interfaces" under the LCD Menu->Configuration. This can assist the user to decide whether or not firmware upgrades are allowed through designated communication ports.
3.	Replaced the battery pack module name from APCRBC132/APCRBC133 to APCRBC157/APCRBC159.
4.	Changed TLS used for  SmartConnect to MbedTLS for cybersecurity.


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
PowerChute Business Edition v9.2
FUW (Firmware Upgrade Wizard) Tool v4.2.1