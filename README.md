# nesUsb
You can make a new oldschool joystick for your PC from an old Nes/Famicom/Simba's junior/Dendy/etc joystick.
At first you need a Digispark Attiny 85 plate. 
All nes/famicom-like joysticks have a 5 wires.
______
Different male connectors and wires in it:

Simba's junior:
\1 o o o o o o 4/
 \2 o o 3 o o 5/

Dendy:
\o o o o o/
 \o o o o/			}- male connectors(or somethin' looks like)

Nes/Famicom:
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
________
Wires should be connected to your Digispark in that way:
Data	- P1(In my code. But you can change it in #define's of preprocessor)

Power	- 5V(Constantly)

Latch	- P1(In my code. But you can change it in #define's of preprocessor)

Ground	- GND(Constantly)

Clock	- P0(In my code. But you can change it in #define's of preprocessor)
