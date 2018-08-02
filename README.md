# MEMS


Microgrid Energy Managment System

It is a protype of a system for managing the generation, load and storage. 
It allows system to run maximum amount of time delivering power to the cretical loads for the purpose of keeping the communication channel router and lamps running. 

Needed:
* Charge Controller 
* APC UPS (powerchute capable)
* Solar Panel
* eGauge
* PWM enabled Relay
* Raspberry Pi
* Lamps


Mems usage intructions:

1. Choose the setting from the menu
  a) The load (Wattage)
  b) Battery (Amp Hour)

System will optimize the loads

* Solar panel can generate up to 250 Watts. 
* The modified battery can run the system for up to 4-10 hours. 
* Loads (Lamps) are controled by the raspberry pi PWM GPIOs

![MEMS Design](/MEMS.png)

*For TechCrunch 2018 Hackaton*
