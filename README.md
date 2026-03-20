# AIoT Smart Industrial Safety Helmet

![Helmet Prototype](images/helmet_prototype.jpg)

## Overview
The AIoT Smart Industrial Safety Helmet is an intelligent safety system designed to monitor workers in hazardous industrial environments.

It integrates IoT sensors and real-time monitoring to detect unsafe conditions and alert workers or supervisors instantly.

---

## Features
- Gas leakage detection
- Motion/impact detection
- Temperature monitoring
- Real-time IoT data transmission
- Worker safety alerts

---

## Problem Statement
Industrial workers are exposed to hazardous environments such as toxic gases, high temperatures, and accidents.  
This system aims to enhance worker safety using real-time monitoring and IoT-based alerts.

---

## Hardware Components
| Component | Description |
|----------|-------------|
| ESP32 | Main microcontroller with WiFi |
| Gas Sensor (MQ Series) | Detects harmful gases |
| Motion Sensor | Detects movement/impact |
| Temperature Sensor | Monitors environment |
| Buzzer | Alert system |
| Power Supply | Battery |

---

## Software & Technologies
- Embedded C / Arduino IDE
- MQTT / WiFi Communication
- IoT Dashboard (Blynk / Custom)

---

## Working Principle
1. Sensors continuously monitor environmental conditions.
2. ESP32 processes sensor data.
3. If unsafe conditions are detected:
   - Buzzer alert is triggered
   - Data is sent to IoT dashboard
4. Supervisors can monitor real-time worker status remotely.

---

## Circuit Diagram
See full connections in the **circuit** folder.

---

## Applications
- Industrial safety monitoring
- Mining industries
- Construction sites
- Hazard detection systems

---

## Future Improvements
- AI-based hazard prediction
- GPS tracking for worker location
- Cloud analytics dashboard
- Machine learning for anomaly detection

---

## Author
Harsha Teja  
Embedded Systems | IoT | AIoT Enthusiast
