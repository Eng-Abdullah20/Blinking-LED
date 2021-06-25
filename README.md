# Robot Eye

This repository contains the hardware, and implentnation descriptions for the design of Robot Eye
Robot Eye Technical Description 
1.	Hardware Description
In this task, the circuit has been designed to be composed of a 555 timer, 12V DC battery, 5 resistors, Two capacitors and two red LEDs. The recharging circuit for the 12V battery is included separately in the design. 
Capacitors Values:
C1=C2=10nF
Resistors Values:
R1=470kΩ
R2=1MΩ
RL=100Ω
R4=240Ω
R5=680Ω
The 555-timer will output a frequency equals to approximately 60Hz according to the following formula f=1.44 / (R1+2×R2) × C1
1.44/(470k+2x1M)x10nF=60Hz, which means the LED will flicker 120 in one second. 
2.	Implementation 
To construct the circuit, first connect the resistors and capacitors as shown in the attached image. From the output terminal connect RL between the pin and ground. Then connect R4 and R5 in parallel with RL. Finally connect the two LEDs in parallel with R4. The advantages of connecting the two LEDs in parallel will allow the LEDs to operate on the same voltage which will enable the LEDs to be brighter, if one of the LEDs turns off the other will still work. 
