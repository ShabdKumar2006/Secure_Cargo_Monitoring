# 🚚 Secure Cargo Monitoring System

A secure cargo monitoring system using **STM32 Nucleo-F446RE** with **real-time Firebase cloud updates**.

---

## 📌 Project Overview
This project is designed to monitor cargo safety during transportation by detecting
unauthorized access or abnormal events, and updating every occurrence to the cloud
for real-time remote monitoring.

---

## 🎯 Objectives
- Detect cargo tampering or unauthorized access
- Log every event securely to Firebase Cloud
- Enable real-time monitoring
- Build a scalable IoT-ready embedded system

---

## 🛠️ Hardware Used
- STM32 Nucleo-F446RE
- Sensors (tamper/intrusion detection)
- Communication module (UART-based)
- Power supply

---

## 💻 Software & Tools
- Embedded C
- STM32CubeIDE
- Google Firebase Realtime Database
- GPIO, UART, Timers

---

## ⚙️ System Architecture
Sensor → STM32 → Communication Module → Firebase Cloud

---

## 🔑 Key Features
- Real-time cargo monitoring
- Cloud update for every occurrence
- Event logging in Firebase
- Secure and reliable embedded design

---

## 🚀 Future Enhancements
- GPS-based cargo tracking
- Mobile app dashboard
- Alert notifications (SMS / Push)
- Encrypted cloud communication

---

## 👨‍🎓 Author
**Shabd Kumar**  
B.Tech | Embedded Systems & IoT | Cambridge Institute of Technology

## 🔐 Security Notice
Sensitive credentials such as Wi-Fi details and cloud server endpoints
have been removed from this repository for security reasons.
Use the provided config_template.h file to add your own credentials.

