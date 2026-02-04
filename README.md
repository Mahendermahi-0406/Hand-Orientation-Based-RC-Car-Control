# Gesture-Controlled RC Car
This project showcases a hand gesture-controlled RC car using Arduino, MPU6050, and RF communication modules. The car responds to the tilt and orientation of the user's hand to move in different directions, providing a hands-free control experience.
<img width="998" height="659" alt="image" src="https://github.com/user-attachments/assets/da4db020-589c-4dfc-b4cb-6aac932f0692" />

**🚗 Project Overview**
* Input Device: MPU6050 (Accelerometer + Gyroscope)
* Wireless Transmission: 434 MHz RF Transmitter & Receiver
* Microcontrollers: 2x Arduino UNO
* Actuators: 2x BO DC Motors driven by L293D Motor Driver
* Power: 9V Battery (prototype) and 12V 4-cell battery (planned)
  
**🧰 Components Used**
| Component | Quantity | Purpose |
| :--- | :--- | :--- |
| **Arduino UNO** | 2 | One for transmitter, one for receiver module |
| **MPU6050** | 1 | Captures hand orientation data |
| **RF Transmitter & Receiver (433 MHz)** | 1 pair | Wireless communication between modules |
| **L293D Motor Driver** | 1 | Controls the DC motors |
| **BO DC Motors** | 2 | Drive the car |
| **Servo Motors** | 2 | (Optional) For steering or accessories |
| **BO Wheels** | 4 | Mobility |
| **12V 4-cell Battery** | 1 | For power (not available during testing) |
| **9V Battery** | 1 | Used for hand module |
| **Wires, Breadboard, Chassis** | Various | Connections and structure |

**📡 Communication Protocol**
* Data from MPU6050 is processed on the transmitter Arduino.
* Specific gyroscopic values are converted into control signals.
* These signals are transmitted via RF module.
* Receiver Arduino interprets signals and drives motors accordingly.

 **🛠️ Circuit & Electronics (Simulation) **
 Due to TinkerCAD limitations (missing MPU6050 and RF modules), simulation uses:
 * Flex sensors to mimic gesture input.
 * Serial communication (TX/RX) between two Arduinos instead of RF.
 * 9V battery instead of unavailable 12V supply.
   <img width="1537" height="823" alt="image" src="https://github.com/user-attachments/assets/f1a464b4-fdec-4a33-ae2f-158743702162" />
   Note: Real-world setup includes MPU6050 and RF communication, not represented in TinkerCAD.
   
**🧩 3D Design & Assembly**
* A custom 3D model of the RC car was designed for laser cutting.
* The chassis was cut using acrylic sheets with slots for motors, Arduino, and sensors.

 **🧠 Learning Outcomes **
 * MPU6050 interfacing and signal processing
 * RF communication implementation
 * Motor driver integration with Arduino
 * 3D design for laser fabrication
 * Full hardware-software integration

 ** 📸 Preview **
 <img width="1275" height="839" alt="image" src="https://github.com/user-attachments/assets/215a280d-d08c-4d95-a16b-1af28ba22bb6" />

**📎 References**
* Arduino Documentation
* MPU6050 Datasheet
* TinkerCAD Circuits
* RF Module Tutorials (Instructables/YouTube)
 
   


 






