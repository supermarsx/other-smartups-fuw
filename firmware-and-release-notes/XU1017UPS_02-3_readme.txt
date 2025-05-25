Version:
========
UPS 02.3

Previous Released Version:
==========================
NA

Applicable SKUs:
================
XU1K3LLXXRCC


Compatibility:
==============
PCBE (future version)
AP9537SUM-FC NMC SUMX (Future version)



Release Notes (UPS 02.3):
========================
1.Fan detection logic improved
2.After firmware upgrade, unit is going to fan high speed, which is removed as it is not necessary


------------release history--------------

Release Notes (UPS 02.2):
========================
1.Microlink map changed V2.0.2, removed BatterySystem.SKU_STR,HighEfficiency
OutputSystem.LowerAcceptableVoltageSetting and OutputSystem.UpperAcceptableVoltageSetting from map
2.Field issue-Fan inoperative issue, firmware logic implemented
3.Field issue-SOC not reaching 100% implemented
4.Battery Disconnect logic is improved, as because of the sensing issue in few units, 
unit is not detecting as battery disconnected when battery is removed
5.UPS-serial-Modbus configuration setting enabled from UI
6.Charger is ON,When Battery AH is selected to '0AH'.
Battery Temp sensor connected or disconnected, charger will be ON
7.Controlled Bypass pass through mode, on giving output off command when unit is in Online/Onbattery, load is not supported.

Release Notes (UPS 01.4):
========================
1.  Initial Release Pilot   