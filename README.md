# Wi-Fi Deauthentication Attack Detector using ESP32

## Overview

This project is a real-time Wi-Fi Deauthentication Attack Detection System developed using the ESP32 microcontroller. The system monitors nearby wireless traffic in promiscuous mode and detects suspicious deauthentication frames commonly used in Wi-Fi denial-of-service attacks.

The project also includes a real-time SOC-style dashboard for monitoring wireless threats, attack statistics, packet activity, and network behavior.

This project combines Cybersecurity, IoT, Embedded Systems, and Real-Time Monitoring concepts.

---

# Features

* Real-time Wi-Fi packet sniffing
* Deauthentication attack detection
* Promiscuous mode packet monitoring
* Live SOC dashboard
* Wireless threat monitoring
* Attack alert system
* MAC address tracking
* RSSI signal monitoring
* Channel monitoring
* WebSocket real-time updates
* Buzzer and LED alerts
* Local web interface
* Lightweight embedded security solution

---

# Technologies Used

## Hardware

* ESP32 Development Board
* Buzzer Module
* LED Indicators
* USB Power Interface

## Programming Languages

* C++
* HTML
* CSS
* JavaScript

## Libraries & Frameworks

* WiFi.h
* esp_wifi.h
* WebServer.h
* WebSocketsServer
* ArduinoJson
* ESPAsyncWebServer

## Cybersecurity Concepts

* Wireless Packet Sniffing
* Deauthentication Attack Detection
* Wireless Intrusion Detection System (WIDS)
* Threat Monitoring
* Packet Analysis
* Real-Time Alerting

---

# How the Project Works

## Step 1: Enable Promiscuous Mode

The ESP32 is configured in promiscuous mode to capture all nearby Wi-Fi packets.

## Step 2: Packet Monitoring

The ESP32 continuously listens for:

* Beacon frames
* Probe requests
* Authentication packets
* Deauthentication packets

## Step 3: Detect Deauth Frames

The detector checks packet frame types and identifies deauthentication frames.

## Step 4: Threat Analysis

The system counts suspicious packets and checks for abnormal activity patterns.

## Step 5: Trigger Alert

If the attack threshold is exceeded:

* Dashboard alert generated
* Buzzer activated
* Warning displayed
* Attack logs updated

## Step 6: Real-Time Dashboard

A local web dashboard displays:

* Attack statistics
* Threat alerts
* Packet activity
* Network monitoring
* Live updates

---

# System Architecture

```text
Nearby Wi-Fi Traffic
          ↓
ESP32 Promiscuous Mode
          ↓
Packet Capture Engine
          ↓
Frame Analysis
          ↓
Deauthentication Detection
          ↓
Threat Classification
          ↓
Dashboard + Alerts
```

---

# Applications

* Wireless Security Monitoring
* Educational Cybersecurity Projects
* SOC Demonstrations
* Embedded Security Research
* IoT Security Systems
* Wireless Intrusion Detection
* Network Threat Analysis

---

# Advantages

* Low-cost security solution
* Real-time attack monitoring
* Portable system
* Lightweight architecture
* Easy deployment
* Embedded cybersecurity implementation
* No external server required

---

# Limitations

* Cannot block attacks directly
* Limited hardware processing power
* Works only within Wi-Fi range
* Cannot decrypt encrypted traffic
* Detection accuracy depends on traffic conditions

---

# Future Improvements

* AI-based anomaly detection
* Telegram alerts
* Cloud dashboard integration
* MQTT support
* Packet logging export
* Rogue Access Point detection
* Evil Twin attack detection
* Mobile application support
* Multi-channel monitoring
* GPS-based attack mapping

---

# Skills Demonstrated

## Cybersecurity Skills

* Wireless Security
* Packet Analysis
* Threat Detection
* SOC Monitoring
* Intrusion Detection

## Embedded Systems Skills

* ESP32 Development
* IoT Programming
* Real-Time Processing
* Hardware Integration

## Web Development Skills

* Dashboard Development
* Real-Time Data Visualization
* Frontend Design
* WebSocket Communication

---

# Use Cases

This project is suitable for:

* Final Year Projects
* Cybersecurity Portfolio
* Internship Demonstrations
* Embedded Security Research
* Wireless Security Learning
* IoT Security Demonstrations

---

# Setup Instructions

## Requirements

* ESP32 Board
* Arduino IDE
* ESP32 Board Package Installed
* Required Libraries Installed

## Upload Steps

1. Connect ESP32 to PC
2. Open Arduino IDE
3. Select ESP32 board
4. Install required libraries
5. Upload the code
6. Open Serial Monitor
7. Connect to ESP32 Access Point
8. Open local dashboard IP

---

# Dashboard Features

* Real-time packet monitoring
* Threat counters
* Signal strength visualization
* Channel activity display
* Attack notifications
* Security event logs
* Live traffic updates

---

# Educational Purpose Notice

This project is developed strictly for:

* Educational purposes
* Security research
* Ethical cybersecurity learning
* Defensive monitoring

Unauthorized use against networks without permission is not recommended.

---

# Author

Bhargav Patel

Cybersecurity | IoT | Embedded Security | SOC Monitoring
