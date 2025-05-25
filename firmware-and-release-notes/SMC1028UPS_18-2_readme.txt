Version: UPS 18.2(SMC)
Applicable SKUs:
================
ID 1028, All standard SKUs beginning with SMC prefixes.
SMC: SMC1000C, SMC1000‐2UC, SMC1500C, SMC1500‐2UC, SMC1000IC, SMC1000I‐2UC,
SMC1500IC, SMC1500I‐2UC
Change logs
1. This correction fixes the incorrect display on the LCD panel of product
keys, such as incomplete digital content or incorrectly displaying 'c'
and 'd' as '9' in the first left‐hand digit of a group of 3 digits.
Note: Smart‐UPS Firmware Upgrade Wizard tool
always includes the latest released firmware and helps upgrade the UPS code.
Link to tool ‐ https://www.apc.com/us/en/faqs/FA279197/
Version: UPS 18.0(SMC)
Applicable SKUs:
================
ID 1028, All standard SKUs beginning with SMC prefixes.
SMC: SMC1000C, SMC1000‐2UC, SMC1500C, SMC1500‐2UC, SMC1000IC, SMC1000I‐2UC,
SMC1500IC, SMC1500I‐2UC
Change logs
1. Fixed an indication issue that EnergyHour stopped counting up.
Note: Smart‐UPS Firmware Upgrade Wizard tool
always includes the latest released firmware and helps upgrade the UPS code.
Link to tool ‐ https://www.apc.com/us/en/faqs/FA279197/
Version: UPS 17.0(SMC)
Applicable SKUs:
================
ID 1028, All standard SKUs beginning with SMC prefixes.
SMC: SMC1000C, SMC1000‐2UC, SMC1500C, SMC1500‐2UC, SMC1000IC, SMC1000I‐2UC,
SMC1500IC, SMC1500I‐2UC
This revision revives the communication of the USB port while the UPS is on
“suspend” mode when the PCBE starts recommunicating.
Change logs:
1. Increase the detection of the USB D‐ signal to escape the “suspended”
Note: Smart‐UPS Firmware Upgrade Wizard tool
always includes the latest released firmware and helps upgrade the UPS code.
Link to tool ‐ https://www.apc.com/us/en/faqs/FA279197/
Version: UPS 16.5(SMC)
Applicable SKUs:
================
ID 1028, All standard SKUs beginning with SMC prefixes.
SMC: SMC1000C, SMC1000‐2UC, SMC1500C, SMC1500‐2UC, SMC1000IC, SMC1000I‐2UC,
SMC1500IC, SMC1500I‐2UC
This revision provides stronger network data security protection via the below
mechanisms, to prevent malicious firmware from being upgraded to the UPS
through communication interface ports (including RJ45).
Change logs:
1. The mechanism of firmware signing adds to the code in order to protect the
UPS from malicious firmware spoofs. Based on the above, firmware upgrade
via NMC is re‐enabled. (model‐dependent)
2. Added the selection of "Firmware Update Interface" under LCD Menu‐>
Configuration. This helps users decide whether to allow performing
firmware upgrades through the communication ports. The icon indicates
"FU.1" to enable all interface communication ports, and "FU.0" to disable
all ports. "FU.2" is set by the communication application.
3. Changed TLS used for SmartConnect to the MbedTLS for cybersecurity.
Note: Smart‐UPS Firmware Upgrade Wizard tool
always includes the latest released firmware and helps upgrade the UPS code
via serial(RS232) port; Upgrade via USB port from this tool is not recommended.
Link to tool ‐ https://www.apc.com/us/en/faqs/FA279197/
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