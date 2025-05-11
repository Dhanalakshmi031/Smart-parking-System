# Smart-parking-System
Smart Parking System using IoT
📖 Abstract
This project presents an IoT-based Smart Parking System that helps manage and reserve parking spots using real-time data, mobile applications, and web interfaces. It automates the process of identifying available parking spaces, allows users to reserve a spot remotely, and provides real-time updates, reducing traffic congestion and time spent searching for parking.

🚀 Features
Real-time parking space detection using sensors (Ultrasonic, IR, PIR)

ESP32-based microcontroller for processing and communication

Online booking system via a web portal

Live updates on parking availability with slot visualization

SMS alert system for slot confirmation and updates

LCD display interface in parking area

Automatic barrier control using micro servo

Online payment integration (planned)

🧠 Technologies & Components
Microcontroller: ESP32

Sensors: PIR, Ultrasonic, IR

Display: LCD (with I2C module)

Control: Micro Servo 9g

Connectivity: Wi-Fi (HTTP, MQTT, or CoAP)

Cloud: Firebase / Custom Web Server

Frontend: HTML, CSS, JavaScript

Backend: Python/Node.js (optional)

Database: Firebase Realtime DB / MySQL

🛠️ System Architecture
The system is built with three core layers:

Sensing Layer – Detects real-time slot occupancy using sensors.

Network Layer – Transfers sensor data to cloud/server.

Application Layer – Displays availability, allows reservations and real-time interaction.

🔁 Workflow Overview
plaintext
Copy
Edit
[Sensor Detected Change] → [ESP32 Sends Update] → [Cloud DB] → [Web/App Display]
🌐 Web Features
Book slots remotely

View total, booked, and available slots

Real-time color-coded status (Green = Available, Red = Booked)

Slot timing and history logs
✉️ Contact
For queries or suggestions, please reach out:
For contact 
📧 [dhanam7071@gmail.com]

