Version:  UPS 18.0(SMT)
Applicable SKUs:
================
ID 1015, All standard SKUs beginning with SMT prefixes.

SMT: SMT750C, SMT750RM2UC, SMT1000C, SMT1000RM2UC, SMT1500C, SMT1500RM2UC, SMT2200C,     
SMT2200RM2UC, SMT3000C, SMT3000RM2UC, SMT750IC, SMT750RMI2UC, SMT1000IC, SMT1000RMI2UC, SMT1500IC, SMT1500RMI2UC, SMT2200IC, SMT2200RMI2UC, SMT3000IC, SMT3000RMI2UC
 
Change logs
1.	Fixed an indication issue that EnergyHour stopped counting up.


Note: The Smart-UPS Firmware Upgrade Wizard tool always includes the latest firmware and helps you to upgrade to the UPS. For more information on the tool, see FA279197.



Version:  UPS 17.2(SMT)
Applicable SKUs:
================
ID 1015, All standard SKUs beginning with SMT prefixes.

SMT: SMT750C, SMT750RM2UC, SMT1000C, SMT1000RM2UC, SMT1500C, SMT1500RM2UC, SMT2200C,     
SMT2200RM2UC, SMT3000C, SMT3000RM2UC, SMT750IC, SMT750RMI2UC, SMT1000IC, SMT1000RMI2UC, SMT1500IC, SMT1500RMI2UC, SMT2200IC, SMT200RMI2UC, SMT3000IC, SMT3000RMI2UC
 
Change logs
1.	Added a patch code for the affected SKUs as below to fix the RBC indication on the LCD panel with the correct RBC string, affected SKUS SMT3000IC, SMT3000C, SMT2200RMI2UC and SMT2200RM2UC.


Note: The Smart-UPS Firmware Upgrade Wizard tool always includes the latest firmware and helps you to upgrade to the UPS. For more information on the tool, see FA279197.



Version:  UPS 17.0(SMT)
Applicable SKUs:
================
ID 1015, All standard SKUs beginning with SMT prefixes.

SMT: SMT750C, SMT750RM2UC, SMT1000C, SMT1000RM2UC, SMT1500C, SMT1500RM2UC, SMT2200C,     
SMT2200RM2UC, SMT3000C, SMT3000RM2UC, SMT750IC, SMT750RMI2UC, SMT1000IC, SMT1000RMI2UC, SMT1500IC, SMT1500RMI2UC, SMT2200IC, SMT2200RMI2UC, SMT3000IC, SMT3000RMI2UC

This revision revives the communication of the USB port while the UPS is on 
“suspend” mode when the PCBE starts recommunicating.

Change logs:
1.	Increase the detection of the USB D- signal to escape the “suspended”


Note: Smart-UPS Firmware Upgrade Wizard tool 
always includes the latest released firmware and helps upgrade the UPS code.
Link to tool - https://www.apc.com/us/en/faqs/FA279197/



Version:  UPS 15.5(SMT)
Applicable SKUs:
================
ID 1015, All standard SKUs beginning with SMT prefixes.

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



Version:  UPS 04.6(SMT) & UPS 04.3(SMC)
Applicable SKUs:
================
ID 1015 and 1018, All standard SKUs beginning with SMT and SMC prefixes.

SMT: SMT750C, SMT750RM2UC, SMT1000C, SMT1000RM2UC, SMT1500C, SMT1500RM2UC, SMT2200C,     
SMT2200RM2UC, STM3000C, SMT3000RM2UC, SMT750IC, SMT705RMI2UC, SMT1000IC,      SMT1000RMI2UC, SMT1500IC, SMT1500RMI2UC, SMT2200IC, SMT200RMI2UC, SMT3000IC, SMT3000RMI2UC
SMC: SMC1000C, SMC1000-2UC, SMC1500C, SMC1500-2UC, SMC1000IC, SMC1000I-2UC,     
     SMC1500IC, SMC1500I-2UC


This release includes remediations for the security vulnerabilities listed as CVE-2022-22805, CVE-2022-22806 and CVE-2202-0715 which, if compromised, may allow for potential unauthorized access and control of the device.

Change logs:
1.	Function implemented to disable UPS firmware upgrades via NMC to mitigate
potential risk of malicious UPS firmware being passed through this channel.
2.	Enhanced UPS firmware code protection to mitigate the vulnerabilities of un-       
authorized extraction of confidential firmware and un-authorized network access to SmartConnect UPSs.



Version:  UPS 04.4
Applicable SKUs:
================
ID 1015, All standard SKUs beginning with SMT prefixes.

SMT: SMT750C, SMT750RM2UC, SMT1000C, SMT1000RM2UC, SMT1500C, SMT1500RM2UC, SMT2200C, 
     SMT2200RM2UC, SMT3000C, SMT3000RM2UC, SMT750IC, SMT750RMI2UC, SMT1000IC,   
     SMT1000RMI2UC, SMT1500IC, SMT1500RMI2UC, SMT2200IC, SMT2200RMI2UC, SMT3000IC,   
     SMT3000RMI2UC

Change logs:
	1.  Pre-charge control optimization on SKUs over 2.2kVA.
	2.  New SKUs supported .
	3.  Solved bug: occasionally zero run time report during battery disconnect.
	4.  Solved bug: “LoadShedRunTimeRemainingSetting”, 
          “LoadShedTimeOnBatterySetting” value is incorrect and unable to write 
          from UPS (Serial & TCP/IP) Modbus 
	5.  Solved bug: incorrect Modbus register “UPSStatusChangeCause” data when  
          power on/off by LCD UI.



Version:  UPS 04.1
Applicable SKUs:
================
ID 1015 and 1018, All standard SKUs beginning with SMT and SMC prefixes.
SMT: SMT750C, SMT750RM2UC, SMT1000C, SMT1000RM2UC, SMT1500C, SMT1500RM2UC, SMT2200C, 
     SMT2200RM2UC, STM3000C, SMT3000RM2UC, SMT750IC, SMT705RMI2UC, SMT1000IC, 
     SMT1000RMI2UC, SMT1500IC, SMT1500RMI2UC, SMT2200IC, SMT200RMI2UC, SMT3000IC, 
     SMT3000RMI2UC
SMC: SMC1000C, SMC1000-2UC, SMC1500C, SMC1500-2UC, SMC1000IC, SMC1000I-2UC, 
     SMC1500I, SMC1500I-2UC

Change logs:
1.	Solved the problem upper acceptable limit can't be set to 276V when output 
voltage setting is 240V. 
	2. Improved charging profile for SMT750IC and SMT750RMI2UC.
	3. Added feature of Modbus over TCP, not include SMC series.
	4. Fixed two report usages of USB HID on ShutdownImminent and 
   DelayBeforeReboot. (DVT 2.2.4)
	5. Implemented EnergyStar2.0/DOE function to improve efficiency based on 
   hardware change.
	6. Fixed the minimum and maximum limit for reported usages of battery run time 
   and shutdown countdown in an application of Linux, NUT.
	7. Fixed that unit did not properly show battery temperature in °F below 
   Freezing.
	8. Fixed communication lost happening frequently with PCBE.
	9. RemainingTimeLimit and AudibleAlarmControl misuse mutually in USB report 
   lufa APC asyncs.
	10. Implement f/w solution to fixed the Jira issue-1145.
	11. Add 125V output configuration to replace 127V.
	12. Change the high line retransfer point of 125V output at poor quality. 



Previous Released Version(from cloud): UPS 03.5
Version:  UPS 03.5
Applicable SKUs:
================
ID 1015 and 1018, All standard SKUs beginning with SMT and SMC prefixes.
SMT: SMT750C, SMT750RM2UC, SMT1000C, SMT1000RM2UC, SMT1500C, SMT1500RM2UC, SMT2200C, 
     SMT2200RM2UC, STM3000C, SMT3000RM2UC
SMC: SMC1000C, SMC1000-2UC, SMC1500C, SMC1500-2UC, SMC1000IC, SMC1000I-2UC, 
     SMC1500I, SMC1500I-2UC

Change logs:
1.	Implement DOE function to improve power efficiency.
2.	Improved SmartConnect cloud connectivity and ability to reconnect to the cloud over time 
3.	Reporting UPS events (for example: battery disconnected, output on, etc) more accurately to SmartConnect cloud server.



Previous Released Version: UPS 03.2
Applicable SKUs:
================
ID 1015 and 1018, All standard skus beginning with SMT and SMC prefixes.
SMT: SMT750C, SMT750RM2UC, SMT1000C, SMT1000RM2UC, SMT1500C, SMT1500RM2UC, SMT2200C, 
     SMT2200RM2UC, STM3000C, SMT3000RM2UC
SMC: SMC1000C, SMC1000-2UC, SMC1500C, SMC1500-2UC

Change logs:
	1.	Enable boost charger function.
	2.	Improve the battery over-temperature-protection function.  The UPS will 
pop-up message on LCD for user to recognize.
	3.	Added an OEM feature - auto turn on when AC is within range.
	4.	Allow configuration and acknowledgement of Site Wiring Fault.
	5.	Added an event reporting to could when Outlet status changes.
	6.	Fixed reversed setting in Modbus configuration. 
	7.	Improved a status reporting to cloud related with pending off for UPS.
8.	LCD Display of runtime remaining when runtime less than one minute will report “< 1m”
9.	Change default choice for confirming installation of firmware now (output on) to CONFIRMED, not CANCEL.



Initial Released Version: UPS 02.6
Applicable SKUs:
================
SMT: SMT750C, SMT750RM2UC


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

