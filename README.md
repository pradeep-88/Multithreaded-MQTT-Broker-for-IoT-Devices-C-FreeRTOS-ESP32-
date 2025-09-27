[![ESP32](https://img.shields.io/badge/Chip-ESP32-success?logo=espressif)](https://www.espressif.com/en/products/socs/esp32)
[![ESP8266](https://img.shields.io/badge/Chip-ESP8266-success?logo=espressif)](https://www.espressif.com/en/products/socs/esp8266)
[![MQTT](https://img.shields.io/badge/MQTT-v3.1.1-yellow?logo=mqtt)](https://mqtt.org/)
![QoS](https://img.shields.io/badge/QoS-0-red)
![C++](https://img.shields.io/badge/Language-C++-blue?logo=c%2B%2B)
![FreeRTOS](https://img.shields.io/badge/RTOS-FreeRTOS-blue)
[![Arduino](https://img.shields.io/badge/Platform-Arduino-green?logo=arduino)](https://www.arduino.cc/)

# 🚀 Lightweight MQTT Broker for Embedded Devices  

A custom **MQTT Broker** designed specifically for resource-constrained IoT boards like **ESP32** and **ESP8266**.  
Developed in **C++** and powered by **FreeRTOS**, this broker supports **multithreading** and efficient message routing, enabling real-time communication between multiple devices in edge environments.  

---

## ✨ Key Features  

- ⚡ **Embedded-first design** – lightweight and optimized for ESP32/ESP8266.  
- 🧵 **Multithreaded client handling** using FreeRTOS tasks for concurrent communication.  
- 🌳 **Prefix tree–based topic management** for faster lookups and reduced memory overhead.  
- 📡 **MQTT v3.1.1 protocol** with **QoS 0** support for low-latency message delivery.  
- 📊 **Benchmark tested** – re-sends **10,000 topics in under 8 seconds** on ESP32.  
- 🔒 **Modular and scalable** – structured with GRASP design principles and event-driven architecture.  

---

## 📂 Example Usage  

- **Basic MQTT Broker** → Initialize and start a broker to handle device-to-device communication.  
- **Broker + HTTP Server** → Run both services in parallel within the same sketch for integrated IoT applications.  

---

## ⚙️ Installation  

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/EmbeddedMQTTBroker.git
   cd EmbeddedMQTTBroker
