# Wearable Blood Blockage Detection

## Overview

The Wearable Blood Blockage Detection system is a healthcare monitoring solution designed to continuously monitor vital health parameters such as heart rate and body temperature. The system detects abnormal readings in real time and sends instant SMS alerts, enabling timely medical attention and improving patient safety.

---

## Features

- Real-time heart rate monitoring
- Continuous body temperature monitoring
- Detection of abnormal health conditions
- Instant SMS alert notifications
- Portable wearable healthcare solution
- Low-cost embedded system implementation

---

## Technologies Used

### Hardware
- Arduino Nano
- Pulse Sensor
- Temperature Sensor (LM35)
- GSM Module (SIM800L/SIM900A)
- OLED Display (Optional)
- Battery Power Supply

### Software
- Arduino IDE
- Embedded C

---

## Components Used

| Component | Purpose |
|----------|---------|
| Arduino Nano | Main microcontroller for processing sensor data |
| Pulse Sensor | Measures the user's heart rate |
| LM35 Temperature Sensor | Monitors body temperature |
| GSM Module (SIM800L/SIM900A) | Sends SMS alerts during emergencies |
| OLED Display (0.96" I2C) | Displays heart rate and temperature readings (optional) |
| Rechargeable Battery | Powers the wearable device |
| Jumper Wires | Electrical connections between components |
| Breadboard/PCB | Circuit assembly and prototyping |
| Power Switch | Turns the device ON/OFF |

---

## Working Principle

The wearable device continuously collects heart rate and body temperature data using sensors connected to an Arduino Nano. The collected data is compared with predefined threshold values. When abnormal readings are detected, the GSM module automatically sends an SMS alert to the registered mobile number, allowing quick response during emergency situations.

---

## Results

- Successfully monitored heart rate and body temperature in real time.
- Detected abnormal health conditions based on predefined threshold values.
- Sent SMS alerts instantly using the GSM module.
- Demonstrated a reliable and portable healthcare monitoring system.

---

## Future Enhancements

- Mobile application for live monitoring
- Cloud-based health data storage
- Integration with IoT platforms
- GPS location tracking for emergency response
- Machine Learning-based health prediction

---
