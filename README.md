<div align="center">

# NICO OS

### A WiFi-Controlled Smart Robotic Platform Powered by ESP32

**Designed & Developed by**

## Zahid Khan • Indra Vamsi

---

![GitHub stars](https://img.shields.io/github/stars/zahidkh1/Nico-OS?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/zahidkh1/Nico-OS?style=for-the-badge)
![GitHub repo size](https://img.shields.io/github/repo-size/zahidkh1/Nico-OS?style=for-the-badge)
![License](https://img.shields.io/github/license/zahidkh1/Nico-OS?style=for-the-badge)
![ESP32](https://img.shields.io/badge/ESP32-IoT-blue?style=for-the-badge)
![Arduino](https://img.shields.io/badge/Arduino-C++-00979D?style=for-the-badge)
![Android](https://img.shields.io/badge/Android-App-green?style=for-the-badge)

---

## Intelligent Robotics • IoT • Embedded Systems

</div>

---

# Abstract

Nico OS is an open-source WiFi-controlled robotic platform developed using the ESP32 microcontroller and an L298N motor driver. The project demonstrates how embedded systems, wireless networking, and mobile applications can be combined to create a responsive robotic vehicle for educational, research, and prototyping purposes.

The robot communicates over a local WiFi network using UDP packets transmitted from an Android application. The ESP32 interprets these commands and controls four BO motors through the L298N motor driver, enabling real-time movement with low communication latency.

Nico OS was developed as a practical robotics learning platform emphasizing modular hardware, clean firmware architecture, and future scalability.

---

# Keywords

ESP32 • Robotics • IoT • Embedded Systems • Arduino • Mobile Robotics • UDP Communication • Android Application • WiFi Robot • Autonomous Systems

---

# Table of Contents

- Introduction
- Features
- System Architecture
- Hardware Components
- Software Stack
- Circuit Diagram
- Working Principle
- Repository Structure
- Installation
- Android Application
- Demonstration
- Future Scope
- Contributors
- License

---

# Introduction

Modern robotics increasingly relies on wireless communication and embedded intelligence.

Nico OS was created to provide an affordable and expandable robotics platform that demonstrates wireless robot control using ESP32 technology while remaining accessible for students, hobbyists, and researchers.

The system is designed to be modular, allowing future integration of additional sensors and autonomous capabilities.

---

# Key Features

- WiFi Controlled Robot
- ESP32 Development Board
- Android Mobile Application
- UDP Communication
- Four-Wheel Drive
- L298N Motor Driver
- Modular Firmware
- Expandable Hardware Design
- Beginner Friendly
- Open Source

---

# Hardware Components

| Component | Quantity |
|------------|----------|
| ESP32 Dev Module | 1 |
| L298N Motor Driver | 1 |
| BO Motors | 4 |
| Wheels | 4 |
| 18650 Li-ion Battery | 2 |
| Chassis | 1 |
| Power Switch | 1 |
| Android Smartphone | 1 |

---

# Software Stack

| Software | Purpose |
|-----------|----------|
| Arduino IDE | Firmware Development |
| ESP32 Arduino Core | ESP32 Programming |
| Blueprint.am | Android App Development |
| GitHub | Version Control |
| Android | Robot Controller |

---

# System Architecture

```
          Android Application
                   │
             WiFi Network
                   │
            UDP Communication
                   │
               ESP32 DevKit
                   │
             L298N Driver
             │           │
       Left Motors   Right Motors
```

---

# Working Principle

1. Android application sends movement commands.
2. ESP32 receives UDP packets.
3. Commands are decoded.
4. L298N receives motor signals.
5. Motors rotate accordingly.
6. Robot performs real-time movement.

---

# Circuit Diagram

> Circuit diagram available inside the **images/** directory.

---

# Repository Structure

```
Nico-OS
│
├── app
│   ├── Android Application
│
├── firmware
│   ├── Nico_OS.ino
│
├── docs
│   ├── Project Documentation
│
├── images
│   ├── Robot Images
│   ├── Circuit Diagram
│
├── libraries
│   ├── DataParser
│
├── LICENSE
└── README.md
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/zahidkh1/Nico-OS.git
```

---

## Open Arduino IDE

Install:

- ESP32 Board Package
- Required Libraries

---

## Upload Firmware

Open

```
firmware/Nico_OS.ino
```

Select

```
Board:
ESP32 Dev Module
```

Upload firmware.

---

# Android Application

The Android controller application is located inside

```
app/
```

Install the APK on your Android device.

Connect both the smartphone and ESP32 to the same WiFi network.

---

# Demonstration

🎥 **YouTube Demonstration**

*(Video will be added after project publication.)*

---

# Future Scope

The project is intentionally modular and can be extended with:

- OLED Display
- Ultrasonic Obstacle Avoidance
- Line Following
- Voice Control
- Bluetooth Mode
- Camera Streaming
- ROS Integration
- Autonomous Navigation
- AI Vision
- GPS Navigation

---

# Contributors

## Zahid Khan

Project Lead

Embedded Systems

Firmware Development

Robotics

---

## Indra Vamsi

Application Development

Testing

System Integration

---

# License

This project is licensed under the MIT License.

---

# Acknowledgements

Special thanks to the open-source robotics and Arduino communities whose tools and documentation have greatly contributed to the development of this project.

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a Star!

**Built with passion for Robotics, IoT, and Innovation.**

© 2026 Zahid Khan & Indra Vamsi

</div>
