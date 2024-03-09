# Traffic-Signal-Controller
RTL design for a Traffic signal controller.

Problem statement:
 ○ A busy Highway is intersected by a little used Country Road.
 ○ Detectors C sense the presence of cars waiting on the Country Road.
 ○ With no car is on Country Road, the lights remain Green in the highway direction.
 ○ If vehicle is on the Country Road, highway lights go from Green to Yellow to Red, 
allowing the Country Road lights to become Green.
 ○ These stay Green only as long as a Country Road car is detected but never longer 
than a set interval.
 ○ When conditions are met, farm lights transition from Green to Yellow to Red, 
allowing highway to return to Green.
 ○ Even if Country Road vehicles are waiting, the highway gets at least a set interval 
as Green.
