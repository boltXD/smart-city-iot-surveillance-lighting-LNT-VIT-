# Smart City IoT Project – Intelligent Street Lighting & Surveillance L&T VIT EDU TECH
KARTHIK S 23BMH113
Design and build an intelligent urban environment for city monitoring, incorporating smart surveillance and intelligent street lighting within Cisco Packet Tracer. Automate the system with sensor-triggered actions for surveillance and lighting


## 🎯 Aim
To design and simulate an intelligent urban monitoring system using Cisco Packet Tracer that integrates:
- Automated street lighting based on motion detection
- CCTV surveillance triggered by motion sensors
- Wireless connectivity and cloud logging

---

## 📌 Problem Statement
With increasing urbanization, energy efficiency and real-time surveillance are essential for smart cities. This project aims to implement intelligent street lighting and surveillance that reacts to environmental conditions using IoT sensors in Cisco Packet Tracer.

---

## 📦 Scope of the Solution
- Reduce power consumption using sensor-based streetlights.
- Improve public safety with motion-triggered surveillance.
- Demonstrate wireless IoT integration and cloud/server data logging.
- Scalable and adaptable for smart city deployments.

---

## 🧭 Architecture Overview

### Components:
- Street Lamp (with light + motion sensors and LED)
- CCTV Camera (IoT-enabled)
- Motion Sensor
- Light Sensor
- Wireless Home Gateway
- IoT Server (for data logging)
- PC or Tablet (for monitoring)

### System Behavior:
- **Street Light:** Turns ON when motion is detected (car/person).
- **Surveillance Camera:** Activates recording when motion is detected.
- All devices connect wirelessly to a Home Gateway.
- Events and sensor data are optionally logged to an IoT Server.

---

## 🧰 Components Used

Listed below are the primary Cisco Packet Tracer IoT components:
IoT Street Lamp (with LED, Motion Sensor, and Light Sensor)

IoT Camera

Motion Detector

Wireless Home Gateway

Server (IoT-enabled)

Old Car (for motion simulation)

PC or Tablet


---

## Logic

💡 Intelligent Street Lighting

IF motion is DETECTED AND ambient light is LOW
→ THEN turn ON the streetlight.

IF motion is NOT DETECTED OR ambient light is HIGH
→ THEN turn OFF the streetlight.


📹 Smart Surveillance

IF motion is DETECTED
→ THEN start video recording.

IF no motion is DETECTED
→ THEN stop video recording.

---

## 🎥 Execution Demos

### 📹 Street Light Automation
Triggered by motion detection (using Old Car):
https://github.com/user-attachments/assets/788b38b8-744a-49d3-a86b-762c4d6020f0

### 📹 Smart Surveillance System
CCTV turns ON when motion is detected:
https://github.com/user-attachments/assets/774f12d3-f9e3-41b1-8188-78032421bfe6



---


## 👨‍💻 Author

KARTHIK S
23BMH1133
Smart City IoT Project 


