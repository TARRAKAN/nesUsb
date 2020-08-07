# nesUsb
You can make a new oldschool joystick for your PC from an old Nes/Famicom/Simba's junior/Dendy/etc joystick.
At first you need a Digispark Attiny 85 plate. 
All nes/famicom-like joysticks have a 5 wires.

Different male connectors and wires in it:

Simba's junior:
_________________
\1 o o o o o o 4/
 \2 o o 3 o o 5/

Dendy:
___________
\o o o o o/
 \o o o o/			}- male connectors(or somethin' looks like) 

Nes/Famicom:
_______
|o o o \
|o o o o\

Joystick's wires:
     		|    Marks on controller's plate     |
wire		nes/famicom	Simba's junior	Dendy
 1.	Data	-		DO		-
 2.	Power	-		VDD		-
 3.	Latch	-		PS		-
 4.	Ground	-		VSS		-
 5.	Clock	-		CLK		-

Connect controller's wires to digispark:
Data	-
Power	- 5V
Latch	-
Ground	- GND
Clock	-
