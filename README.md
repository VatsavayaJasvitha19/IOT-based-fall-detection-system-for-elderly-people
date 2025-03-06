Overview
This project presents an IoT-based Fall Detection System designed to assist elderly individuals who live alone and may require immediate medical attention in case of a fall. The system integrates motion sensors, a microcontroller, and cloud-based communication to send real-time alerts to caregivers or family members when a fall is detected.

Features
Real-Time Fall Detection: Utilizes the MPU6050 accelerometer and gyroscope to monitor movement and orientation.
Emergency Alert System: Sends an SOS notification via IFTTT (If This Then That) to caregivers.
Mobile App Integration: Developed using Kodular and Google Firebase, allowing real-time monitoring of fall status.
Buzzer Alert System: Triggers an audible alarm upon fall detection.
Wearable & Embedded Design: The system can be implemented in a wristwatch or waist belt for easy use.
Methodology
Hardware Components:

MPU6050: 3-axis accelerometer and gyroscope for motion tracking.
NodeMCU (ESP8266-12e): Wi-Fi-enabled microcontroller for data processing and cloud communication.
Buzzer: Provides an audible alert when a fall is detected.
Jumper Wires: Connect different components for circuit assembly.
Data Processing:

The MPU6050 sensor captures acceleration and orientation data.
The system calculates an amplitude vector to detect abnormal motion.
If the movement exceeds a predefined threshold, the gyroscope values are checked to confirm a fall.
If confirmed, an alert is sent to a predefined contact via IFTTT.
Mobile App:

Developed using Kodular, a no-code app development platform.
Fetches fall detection status from Google Firebase.
Provides audio alerts when a fall is detected.
System Architecture
Sensor Data Collection: MPU6050 captures motion data.
Data Processing: NodeMCU processes the sensor readings.
Fall Detection Algorithm: Determines whether a fall has occurred.
Alert Mechanism: Triggers buzzer and sends emergency notifications.
Mobile App Integration: Displays real-time fall status.
Results
The system successfully detected falls and triggered SOS notifications.
The mobile app displayed real-time fall status and provided audio alerts.
The buzzer activated upon fall detection, providing an additional warning mechanism.
Future Enhancements
Improved Accuracy: Enhancing the fall detection algorithm to reduce false positives.
Wearable Prototype: Developing a compact device (watch or belt) for real-world use.
AI Integration: Implementing machine learning models to improve detection accuracy.
Contributors
Neha Nandal
Mallikarjuna Rao
Kumudini Mandava
Jasvitha Vatsavaya
Sreeja Yalavarthi
Swetha Chouki
References
For detailed references, see the Research Pape
