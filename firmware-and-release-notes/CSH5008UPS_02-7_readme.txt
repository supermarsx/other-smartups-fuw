Version:
========
UPS 02.7

Applicable Models:
==================
CSH2, CSH2-I, CSH2-JP

Previous Released Version:
==========================
UPS 02.5

Release Notes (UPS01.1):
========================
1. Add MCU flash protection


Release Notes (UPS 02.5):
========================
The issues addressed in this version of code:
1.	Addressed and ensured that AC_Present information is passed to HUB to displat Battery charge plug ICON on HUB within 10 seconds.
2.	Addressed the delay in updating the SoC% details on HUB to display within 6 seconds.
3.	Incorporated a wait time of 5 minutes and for an SoC% of 2% to turn on 24V DC output when AC mains applied after a battery low shutdown.
4.	Incorporated the modification of displaying SoC% only if unit 24V DC output is ON.
