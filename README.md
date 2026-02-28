# Temperature-Controlled-Fan-System-Using-Transistors-
Temperature-Controlled Fan System Using Transistors (Automatic Cooling Circuit)

This project is an automatic temperature-controlled motor system designed to activate a fan when the temperature rises above a defined threshold.

The circuit uses:
•	NTC Thermistor (R1) – Detects temperature changes
•	2N2222A (NPN Transistor) – Acts as a signal amplifier/switch
•	TIP127 (PNP Darlington Transistor) – Drives the motor
•	LED Indicator – Shows when the system is activated
•	12V DC Motor – Acts as a cooling fan

How It Works

At low temperature (e.g., 30°C):
1.	The thermistor resistance is high.
2.	The 2N2222A remains OFF.
3.	The TIP127 remains OFF.
4.	The motor (fan) does not rotate.
5.	At high temperature (e.g., 50°C and above):
6.	The thermistor resistance decreases.
7.	This activates the 2N2222A.
8.	The TIP127 is driven into conduction.
9.	The motor turns ON and starts cooling.
10.	The LED lights up to indicate activation.

<img width="1090" height="1026" alt="image" src="https://github.com/user-attachments/assets/26cb2d32-f2b2-4e22-b01e-4eb0afce2125" />
<img width="1090" height="1042" alt="image" src="https://github.com/user-attachments/assets/dd2a5890-03bb-4d8f-845a-6e6ad68a1271" />
<img width="578" height="1027" alt="image" src="https://github.com/user-attachments/assets/157c80be-64c3-4954-818e-3b7b02565083" />

<img width="578" height="1027" alt="image" src="https://github.com/user-attachments/assets/4d9ee681-ddab-487a-91f2-bdb1bfabfa9c" />

