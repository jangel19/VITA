# VITA Health

VITA Health is a wearable health-tech platform currently under development, designed to track real-time biometrics such as heart rate, SpO2, motion, and temperature. The system combines embedded IoT hardware (ESP32 microcontroller + sensors) with a mobile app interface, aiming to deliver accurate, privacy-focused health monitoring.

---

## Status: In Progress

### Project Overview

- The initial version of the VITA app was developed in **Swift** for iOS devices.
- We are currently **migrating the UI to React Native** to optimize performance, scalability, and compatibility across both **Android and iOS** platforms.
- The goal is to create a fast, secure, and responsive cross-platform app with real-time data visualization and long-term health trend analytics.

---

### Hardware & Sensor Integration

We’re currently testing and validating sensor data accuracy and Bluetooth communication protocols.

#### What’s working:
- **ESP32 board** is successfully streaming data via Bluetooth Low Energy (BLE)
- **Heart rate sensor (MAX30102)** is transmitting live pulse and SpO2 data
- **Accelerometer** and **gyroscope** are tracking motion events and orientation
- Basic connectivity and sensor logic is being prototyped in **Arduino IDE**

#### Ongoing Work:
- Calibrating sensor accuracy across different users and conditions
- Testing BLE connection stability and throughput
- Creating fallback mechanisms and alert logic for disconnected states
- Improving battery optimization and packaging for wearability

---

### UI Development (React Native)

The user interface is being rebuilt from the ground up to provide a clean, intuitive, and mobile-first experience. Planned features include:

- 📊 Real-time health metrics dashboard
- 📈 Historical data charting and analytics
- 🛏️ Sleep, activity, and recovery tracking
- 🔒 Secure user authentication and device linking (via Supabase)

---

### Tech Stack

- `ESP32` (Bluetooth Low Energy microcontroller)
- `Arduino IDE` (sensor development & testing)
- `MAX30102` (SpO2 + Heart Rate sensor)
- `Accelerometer` / `Gyroscope`
- `React Native` (upcoming UI framework)
- `Supabase` (user auth & cloud database)
- `Figma` (UI/UX wireframing)

---

### Timeline

This is an evolving project with many moving parts — sensor firmware, BLE protocols, and UI logic are being tested and refined in parallel. Our goal is to have an MVP ready for demo in late 2025/early 2026.

---

### Team

VITA is developed by a team of six passionate student engineers with backgrounds in embedded systems, iOS development, UI/UX, and cloud architecture.

---

### Note

This is a work-in-progress repository. Some components and code will change drastically as we transition away from the original Swift-based app and toward a unified cross-platform codebase. Contributions and feedback are welcome!
