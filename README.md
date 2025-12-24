# VITA Health

VITA Health is a student-built wearable health prototype focused on collecting and visualizing basic biometric and movement data using embedded hardware. The project explores end-to-end data flow from sensors on an ESP32 device to a simple user-facing interface, with an emphasis on embedded systems, Bluetooth communication, and hardware–software integration.

This repository reflects an **early-stage prototype**, not a finished consumer product.

---

## Project Status

**Status:** Prototype / Paused  
**Timeline:** February 2025 – Present  

Core hardware functionality and data flow were implemented and validated. The project is not currently under active feature development.

---

## Project Overview

The goal of VITA Health was to design and prototype a wearable system capable of:

- Collecting heart rate and motion data from onboard sensors  
- Computing basic metrics such as steps, activity level, and heart rate trends  
- Transmitting data wirelessly using Bluetooth Low Energy (BLE)  
- Displaying collected data through a simple web-based interface  

The project was developed as a **team-based engineering effort** to explore embedded firmware, sensor integration, and basic backend data storage.

---

## Hardware & Embedded Systems

**What was implemented:**

- ESP32 microcontroller running Arduino-based C/C++ firmware  
- Heart rate sensor for pulse data collection  
- Accelerometer used to estimate steps and general movement/activity  
- Custom PCB integrating sensors and power components  
- Haptic motor used for basic notifications and alerts  
- BLE communication between the ESP32 and a client interface  

**Firmware responsibilities included:**

- Sensor sampling and signal handling  
- Simple step and activity estimation logic  
- BLE data packaging and transmission  
- Error handling for disconnected or unstable BLE states  

---

## Software & Data Flow

- Sensor data was transmitted from the ESP32 over BLE  
- A lightweight interface was built to display real-time and historical readings  
- Supabase was used for basic data storage and user authentication  
- The software stack was intentionally minimal to focus on validating hardware-to-UI communication  

---

## Tech Stack

**Embedded / Hardware**
- ESP32  
- Arduino-based C/C++  
- Heart rate sensor  
- Accelerometer  
- Custom PCB  
- Haptic motor  

**Software**
- Bluetooth Low Energy (BLE)  
- Supabase (database & auth)  
- JavaScript (basic UI and data display)  

---

## Team & Collaboration

VITA Health was developed by a small student team. Work was divided across:

- Embedded firmware and sensor integration  
- PCB design and hardware assembly  
- BLE communication and data handling  
- Basic UI and backend integration  

My primary contributions focused on **embedded firmware, BLE communication, metric computation, and hardware integration**, while collaborating closely with teammates responsible for UI and system organization.

---

## Notes

- This repository represents a **prototype and learning project**
- Code quality and structure reflect experimentation rather than production standards  
- Some components may be incomplete or simplified  
- The project is intentionally documented honestly to reflect its educational and exploratory nature  

---

## License

This project is shared for educational and demonstration purposes.
