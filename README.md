# 🔌 Seeed Studio XIAO ESP32-C6 Projects

![XIAO ESP32-C6](Files/seeedesp32c6.png)

Welcome to the **XIAO ESP32-C6 Projects Repository**, showcasing embedded IoT experiments and hardware prototypes built around the compact and powerful Seeed Studio XIAO ESP32-C6.

---

## 📦 Board Overview

The **XIAO ESP32-C6** is a **Wi-Fi 6** and **Bluetooth 5** enabled microcontroller with **Thread** and **Matter** support, built for efficient, secure, and scalable IoT development in a thumb-sized package.

### ⚙️ Core Features

- **ESP32-C6 Chip** (32-bit RISC-V Single-core @ 160 MHz)
- **256KB SRAM + 4MB Flash**
- **Wireless**:  
  - Wi-Fi 6 (802.11ax)  
  - Bluetooth 5 LE  
  - IEEE 802.15.4 (Zigbee, Thread support)
- **USB-C + Native USB CDC support**
- **Rich GPIO Access**:
  - 11 GPIOs (I²C, SPI, UART, PWM, ADC, Digital)
  - 1x RGB LED (onboard)
- **Ultra Low Power** Sleep Support (ideal for battery-powered applications)

---

## 🧠 Project Concepts

All projects are coded in **Arduino** or **ESP-IDF** (and optionally **MicroPython**) and stored under `/Projects`.

### 🔧 Project Ideas Include:

- 🔋 **Battery-powered IoT sensors** (sleep & wake using interrupts)
- 📶 **Wi-Fi + Web Dashboard** for sensor data
- 🌐 **Matter/Thread Demos** (coming soon)
- 📷 **BLE device scanners** and mesh networks
- 🔐 **Secure OTA updates** via HTTPS

---


## 🛠️ Example Pin Reference

| Function     | Pin   |
|--------------|-------|
| I²C SDA      | GPIO6 |
| I²C SCL      | GPIO7 |
| Analog Input | A0    |
| PWM Output   | Any GPIO |


---
