\# 🏠 HomeGuard – Multi-Sensor Safety \& Monitoring System



HomeGuard is an embedded multi-sensor safety system designed to enhance residential security and environmental monitoring using Arduino and IoT concepts. The system detects abnormal conditions in real time and generates visual alerts through LEDs and an LCD display.



---



\## 🚀 Project Overview



HomeGuard integrates multiple environmental and security sensors with a microcontroller to monitor critical parameters inside a home environment. When abnormal activity is detected, the system immediately displays alerts on a 16x2 LCD and activates corresponding LED indicators.



This project was developed as part of a hackathon to demonstrate practical real-time embedded system applications focused on home safety.



---



\## 🔧 Hardware Components



\- Arduino Nano  

\- 16x2 LCD Display with I2C Module  

\- PIR Motion Sensor  

\- Door Sensor (Limit Switches)  

\- Water Level Sensor (Copper Wire Based)  

\- Rain Sensor (Copper Coil Based)  

\- High Voltage Detection Module (Zener Diode Based)  

\- LDR (Light Dependent Resistor)  

\- LEDs  

\- Relays  

\- Regulated Power Supply Unit  



---



\## 🧠 System Features



\- Motion detection inside the house  

\- Main gate and door status monitoring  

\- High water level detection to prevent overflow  

\- Rain detection alert  

\- High AC voltage protection mechanism  

\- Light intensity monitoring  

\- Real-time alert messages on LCD  

\- Dedicated LED indication for each sensor trigger  



---



\## ⚙️ Working Principle



The Arduino Nano continuously reads input signals from all connected sensors.  



If any sensor crosses its predefined threshold:

1\. The corresponding alert message is displayed on the LCD.

2\. The specific LED indicator is activated.

3\. Protective actions (via relays) are triggered when required.



The LCD communication is handled using the I2C protocol for efficient pin utilization.



---



\## 💻 Software Specifications



\- \*\*Development Platform:\*\* Arduino IDE  

\- \*\*Programming Language:\*\* Embedded C / C++  

\- \*\*Communication Protocol:\*\* I2C (LCD Interface)  



The firmware runs in a continuous monitoring loop to ensure real-time responsiveness.



---



\## 🌐 Future Enhancements



\- Integration of ESP32 for IoT connectivity  

\- Hosting real-time sensor data on a web server  

\- Remote monitoring via mobile or web application  

\- Cloud-based data logging and alert notifications  

\- Push notifications for emergency alerts  



> Note: ESP32-based remote monitoring was conceptually designed and partially explored but not fully implemented in the current version.



---



\## 🏁 Conclusion



HomeGuard demonstrates a practical implementation of a multi-sensor embedded safety system. The project highlights expertise in hardware interfacing, embedded programming, sensor integration, and system-level design, forming a strong foundation for scalable IoT-based smart home solutions.



---



\## 👩‍💻 Author



\*\*K Yamini\*\*  

Electronics and Communication Engineering  

Embedded Systems \& IoT Enthusiast



