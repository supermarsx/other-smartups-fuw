Version:  UPS 15.6(SCL)
Applicable Models:
==================
ID 1029 with internal NMC sku.

SCL: SCL500RM1UNC, SCL500RMI1UNC

This revision optimizes charging sequence for saving more energy.

Change logs:
1.	Optimize charging sequence for saving more energy.

Note: Smart-UPS Firmware Upgrade Wizard tool 
always includes the latest released firmware and helps upgrade the UPS code. Link to tool - https://www.apc.com/us/en/faqs/FA279197/



Version:  UPS 15.5(SCL)
Applicable Models:
==================
ID 1029 with internal NMC sku.

SCL: SCL500RM1UNC, SCL500RMI1UNC

This revision provides stronger network data security protection via the below mechanisms to prevent malicious firmware from being upgraded to the UPS through communication interface ports.

Change logs:
1.	The mechanism of firmware signing adds to the code in order to protect the UPS from malicious firmware spoofs.

Note: Smart-UPS Firmware Upgrade Wizard tool 
always includes the latest released firmware and helps upgrade the UPS code via serial(RS232) port; Upgrade via USB port from this tool is not recommended.
Link to tool - https://www.apc.com/us/en/faqs/FA279197/



Version:  UPS 15.1(SCL)
Applicable Models:
==================
SCL500RM1UNC, SCL500RMI1UNC
ID 1029 with internal NMC sku.

This release includes remediation for the security vulnerabilities listed as CVE-2022-22805, CVE-2022-22806 and CVE-2202-0715 which, 
if compromised, may allow potential unauthorized access and control of the device.

Change logs:
    1. Function implemented to disable UPS firmware upgrades via NMC to mitigate potential risk of malicious UPS firmware being passed through this channel.
    2. Enhanced UPS firmware code protection to mitigate the vulnerabilities of unauthorized extraction of confidential firmware and un-authorized network access to SmartConnect UPS.
    3. Fix an issue to make the upgrade with Output On feature more stable.

Note: The previous versions may refuse the upgrade with Output On in some special situation. In such cases, please choose a suitable time when the UPS can be turned off without affecting the use of equipment connected to the UPS. Turn off the UPS manually and then upgrade.



Version:  UPS 02.5(SCL)
Applicable Models:
==================
ID 1029 with internal NMC sku.

Change logs:
    1.  500VA 230V sku support
    2.  Negative watt calculation added to fix the issue of large error in the load value.
    3.  Deal with MinkVI 500VA jira issue -18:  Vout transient drop. 
    4.  Fix the issue that battery version shows garbage text on STL battery 
    5.  Modify the low sensitivity blackout detection time  





