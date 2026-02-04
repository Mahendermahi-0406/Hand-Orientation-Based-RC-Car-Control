# Gesture-Controlled RC Car
This project showcases a hand gesture-controlled RC car using Arduino, MPU6050, and RF communication modules. The car responds to the tilt and orientation of the user's hand to move in different directions, providing a hands-free control experience.
<img width="998" height="659" alt="image" src="https://github.com/user-attachments/assets/da4db020-589c-4dfc-b4cb-6aac932f0692" />

🚗 **Project Overview**

🧰 Components Used
Component	Quantity	Purpose
Arduino UNO	2	One for transmitter, one for receiver module
MPU6050	1	Captures hand orientation data
RF Transmitter & Receiver (433 MHz)	1 pair	Wireless communication between modules
L293D Motor Driver	1	Controls the DC motors
BO DC Motors	2	Drive the car
Servo Motors	2	(Optional) For steering or accessories
BO Wheels	4	Mobility
12V 4-cell Battery	1	For power (not available during testing)
9V Battery	1	Used for hand module
Wires, Breadboard, Chassis	Various	Connections and structure
📡 Communication Protocol
Data from MPU6050 is processed on the transmitter Arduino.
Specific gyroscopic values are converted into control signals.
These signals are transmitted via RF module.
Receiver Arduino interprets signals and drives motors accordingly.
🛠️ Circuit & Electronics (Simulation)
Due to TinkerCAD limitations (missing MPU6050 and RF modules), simulation uses:

Flex sensors to mimic gesture input.
Serial communication (TX/RX) between two Arduinos instead of RF.
9V battery instead of unavailable 12V supply.
