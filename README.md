HomeGuard – An Efficient Multi-Sensor Safety System

HomeGuard is a multi-sensor based safety and monitoring system designed to enhance home security and safety using embedded systems and IoT concepts. The system detects abnormal conditions and provides real-time alerts through visual indicators and an LCD display.

🚀 Project Overview

The HomeGuard system integrates multiple safety sensors with a microcontroller to monitor different environmental and security parameters in a house. When any abnormal condition is detected, the corresponding alert message is displayed on an LCD and indicated through LEDs.

This project was designed and implemented as part of a hackathon and focuses on practical, real-time safety applications.

🔧 Hardware Components Used

Arduino Nano

16x2 LCD with I2C module

PIR Motion Sensor

Door Sensor-Limit Switches

Water Level Sensor -Copper wire

Rain Sensor-copper coil

High Voltage Detection Module-Zener Diode

LDR (Light Dependent Resistor)

LEDs

Relays

Power Supply Unit

🧠 System Functionality

Detects abnormal motion inside the house

Monitors main gate and door status

Detects high water level to prevent overflow

Detects rain conditions

Provides high AC voltage protection

Detects light intensity changes

Displays real-time alerts on LCD

Provides LED indication for each sensor trigger

💻 Software Details

Platform: Arduino IDE

Programming Language: Embedded C / C++

Communication Protocol: I2C (for LCD)

The Arduino program continuously monitors the sensor inputs and displays the corresponding alert message on the LCD whenever a sensor is triggered.

📁 Repository Structure

HomeGuard/
├── Arduino_Code/
│ └── homeguard.ino
├── Documents/
│ └── HomeGuard_Block_Diagram.pdf
└── README.md

🌐 Future Enhancements

Integration of ESP32 for IoT connectivity

Hosting sensor data on a web server using IP address

Remote monitoring through mobile or web application

Cloud data logging and alert notifications

Note: The IoT-based remote monitoring module using ESP32 was planned and partially explored but not fully implemented during the current phase of the project.

🏁 Conclusion

HomeGuard demonstrates a practical implementation of an embedded multi-sensor safety system. The project showcases skills in hardware interfacing, embedded programming, and system-level design, and serves as a strong foundation for future IoT-based enhancements.

👩‍💻 Author

K Yamini 
Electronics and Communication Engineering
Embedded Systems & IoT Enthusiast
