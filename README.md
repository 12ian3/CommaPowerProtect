# Comma Power Protect
The comma 2 draws 50mA even while powered off. This is just too much. The calcuation shows that this should last 30 days before fully discharging your car battery, but that's a 100% discharge. You still need some amount of charge in the battery to start your engine. For me, that was about 12 days.  
This project aims to improve upon the stock comma power by adding an adjustable voltage cutoff to the comma power. Thus, when you turn off your car*, the device will discharge your battery down to your set threshold, and then fully turn off**.  
  
Notes:  
\*On some vehicles, the relay harness always provides 12v I believe. On those vehicles, this would prove ineffective.  
\**Leakage current of around 10uA.