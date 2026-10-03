# Autonomous Safari Navigation System

An AI-powered, autonomous navigation and telemetry system designed for smart safari vehicles. This system integrates edge AI, wireless communication, and multiple sensors to ensure safe and efficient field navigation.

## 🚀 Overview
The Autonomous Safari Navigation System is built around the ESP32 ecosystem. It leverages an ESP32-CAM for edge-based computer vision and an ESP32 for robust hardware control. The system automatically navigates predefined paths using IR sensors, stops for obstacles, and logs real-time telemetry (location and vehicle identity) using GPS and RFID modules.

## ⚙️ Key Features
- **Edge AI Vision:** Utilizes an ESP32-CAM to process visual data on the edge for intelligent routing and obstacle detection.
- **Autonomous Navigation:** IR sensors provide continuous feedback for precise line-tracking and path-following capabilities.
- **Real-Time Telemetry:** Integrates GPS for real-time location tracking and RFID for secure vehicle identification and logging.
- **Wireless Command & Control:** Features a web-based dashboard hosted on the ESP32 to monitor telemetry, view camera feeds, and override autonomous controls if necessary.
- **Closed-Loop System:** Combines onboard sensing, wireless telemetry, and automated reporting into a single, cohesive unit for field deployment.

## 🛠️ Hardware & Tech Stack
- **Microcontrollers:** ESP32, ESP32-CAM
- **Sensors:** IR Line Sensors, GPS Module (Neo-6M), MFRC522 RFID Reader
- **Actuators:** DC Motors with L298N/L293D Motor Drivers
- **Languages:** Embedded C / C++ (Arduino Framework)

## 📡 System Architecture
1. **Perception:** IR sensors read the path; the ESP32-CAM processes environmental visual cues.
2. **Processing:** The main ESP32 aggregates sensor data, processes navigation algorithms, and handles RFID authentication.
3. **Action:** Motor drivers execute precise movements based on the processing logic.
4. **Telemetry:** Location and status data are transmitted over Wi-Fi to a monitoring station.

## 👨‍💻 Author
**Devansh Khandar**  
*Electronics & Telecommunication Engineer*
