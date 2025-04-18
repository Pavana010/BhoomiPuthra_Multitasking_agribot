# 🌾 BhoomiPuthra – Solar-Powered Smart Agri-Bot 🚜⚡💧

> **An intelligent, IoT-enabled multi-task farming robot powered by the sun — built to automate, monitor, and protect your crops.**

---

## 🔗 Quick Links

| Section | Link |
|--------|------|
| 📘 Project Overview | [View Overview](#-project-overview) |
| 🎥 Live Demo | [Watch Demo Video](https://youtu.be/your-demo-video-link) |
| 🧠 Features & Stack | [Explore Features](#-key-features) |
| 🛠️ Circuit Diagram | [View Circuit](https://github.com/amruthabn/bhoomiputhra/blob/main/assets/circuit-diagram.png) |
| 💻 Source Code | [ESP32 Code Folder](https://github.com/amruthabn/bhoomiputhra/tree/main/code) |
| 📸 Project Photos | [Photos Folder](https://github.com/amruthabn/bhoomiputhra/tree/main/assets/photos) |

---

## 📘 Project Overview

**BhoomiPuthra** is a smart agricultural robot designed to automate common farming tasks using **renewable solar energy** and **IoT-based remote monitoring**.  
Built around **ESP32 microcontrollers**, it performs:

- 🌿 Grass cutting  
- 💧 Smart water irrigation  
- 🧴 Pesticide spraying  
- 🌡️ Soil & weather monitoring  
- 📷 Live video streaming via ESP32-CAM  
- 🐾 Animal detection with buzzer alert  
- 📱 Remote control via **Dabble App** and **Blynk IoT**

> Designed for real-world farms. Built by engineering students. Powered by the sun.

---

## ⚙️ Technology Stack

| ⚡ Hardware | 🌐 Software |
|------------|------------|
| ESP32 (x2) | Arduino IDE |
| ESP32-CAM | Blynk IoT App |
| DHT11 Sensor | Dabble App (Bluetooth) |
| Soil Moisture Sensor | Firebase (optional) |
| Voltage Sensor | |
| Servo Motors | |
| L293D Motor Driver | |
| Solar Panel & Battery | |

---

## 🚀 Key Features

- 🔋 Solar-powered and eco-friendly  
- 📷 Live video feed from ESP32-CAM  
- 🔧 Dual-processor multitasking (sensors + actuators)  
- 💦 Automated irrigation & pesticide spraying  
- 🐦 Buzzer system to scare animals at night  
- 🌐 Wireless control (Bluetooth & Wi-Fi)  
- 🔁 Real-time data updates and sensor logs  
- 📉 Low cost, high-efficiency, scalable design

---

## 🧠 Future Upgrades

- 🧭 GPS-based autonomous navigation  
- 🧠 AI-based crop health detection  
- 🧪 Soil nutrient testing with NPK sensors  
- ☁️ Cloud dashboard for data visualization  
- 🚁 Drone integration for aerial monitoring

---

## 📸 Project Showcase

| Working Model | Circuit Diagram |
|---------------|-----------------|
| ![Model](https://github.com/amruthabn/bhoomiputhra/blob/main/assets/photos/robot.jpg) | ![Circuit](https://github.com/amruthabn/bhoomiputhra/blob/main/assets/circuit-diagram.png) |

> *(Click images to open full view)*

---

## 🛠️ Installation Guide

```bash
1. Clone the repo:
   git clone https://github.com/amruthabn/bhoomiputhra.git

2. Open Arduino IDE → Install ESP32 board

3. Upload:
   - ESP32_1.ino → Handles movement, cutting, pumping
   - ESP32_2.ino → Handles sensors, seeding, video

4. Connect modules as per circuit diagram

5. Configure:
   - Dabble App (Bluetooth)
   - Blynk IoT (Wi-Fi auth key)

6. Power it up with solar/battery and start farming!
