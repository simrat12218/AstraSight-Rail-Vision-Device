# Agaah-Rail-Vision-Device
# 🚆 Agaah: Rail ki Nayi Disha

AstraSight is an advanced railway safety and situational awareness system designed to enhance train operations by detecting real-time obstacles, ensuring track clearance, and improving communication—all while significantly reducing infrastructure costs.

---

## 🔍 Project Overview

In India, railways form the backbone of transportation, yet frequent accidents and unscheduled delays—especially due to sudden obstructions like animals, humans, or debris on the tracks—continue to pose serious challenges. AstraSight addresses this by integrating cutting-edge technologies to improve safety, efficiency, and decision-making **inside the locomotive** without requiring physical installations on the tracks.

---

## 🎯 Problem Statement

Despite significant investment in traditional signaling and monitoring systems, accidents due to poor visibility, fog, and track intrusions remain common. Current systems are:
- Expensive to install and maintain
- Often dependent on centralized infrastructure
- Limited in remote or fog-prone regions

---

## 🚀 Key Features

- **💡 Real-time Obstacle Detection** using TF-Luna/TFMini LiDAR sensors
- **📡 Long-Range Communication** via LoRa (Low Power Wide Area Network)
- **🖥️ Onboard TFT Display** to show live distance readings, track clearance, and signal status
- **🚦 LED-based Safety Signals** (Red-Yellow-Green) based on LiDAR and LoRa input
- **🛰️ GPS Integration (Future Scope)** for geotagged alerts and route tracking
- **🧠 Powered by FreeRTOS** for multitasking and responsive real-time performance
- **📉 Cost-Optimized Design** with up to **60% cost savings** compared to traditional systems

---

## 💰 Why AstraSight?

- **No trackside hardware needed** – all components are locomotive-mounted
- **Minimal infrastructure modification**
- **Open, modular, and scalable design**
- **60%+ cost reduction** compared to conventional obstacle detection and signaling solutions
- **Built with affordable microcontrollers (STM32), sensors, and open protocols**

---

## 📦 Tech Stack

- **Microcontroller**: STM32 Nucleo-F446RE
- **Sensors**: TF-Luna / TFMini LiDAR
- **Communication**: LoRa SX1278 modules
- **Display**: 1.8”/2.4” SPI TFT LCD
- **Real-Time OS**: FreeRTOS
- **Programming**: Embedded C/C++, STM32CubeIDE
- **Optional (Future)**: GPS Module (NEO-6M), Wi-Fi/IoT backend, Map interface (OpenRailwayMap)

---

## 📌 Applications

- Collision avoidance in fog, night, or hilly terrain
- Remote track clearance monitoring
- Smart signaling in semi-automated trains
- Early warning system for loco pilots
- Retrofit solution for older locomotives

---

## 🌱 Project Status

✅ MVP with LiDAR + Display + LoRa + FreeRTOS working  
🔄 Integration with GPS and backend web dashboard in progress  
🚧 Prototype testing under various simulated conditions (fog, tunnel)

---

## 🤝 Contributing

Have ideas to improve AstraSight or want to integrate new features like AI-based object recognition or map visualizations? We welcome contributions! Fork the repo, raise an issue, or submit a PR.

---

## 🙏 Acknowledgements

This project draws inspiration from real-world railway safety challenges in India and aims to offer a **cost-effective, indigenous solution**. Developed as part of railway safety innovation initiatives and Smart India Hackathon explorations.

---

> 🚆 *AstraSight – Towards Safer, Smarter, and More Efficient Indian Railways*

