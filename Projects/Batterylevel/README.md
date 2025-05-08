# 🔋 Battery Voltage Monitor with XIAO ESP32-C6 + 220kΩ Divider

![XIAO ESP32C6](https://github.com/jhherre3/XIAO-ESP32-C6/blob/main/Files/checkbattery.png)

This project reads and displays the **battery voltage level** using a **custom voltage divider** built with two **220kΩ resistors**, allowing the Seeed Studio **XIAO ESP32-C6** to safely monitor Li-ion or LiPo battery levels.

---

## 🎯 Project Overview

- 📟 Reads actual battery voltage (e.g., 3.0V–4.2V)
- 🔋 Uses analog pin `A0` (GPIO1)
- 🛠️ Adds a **220kΩ : 220kΩ** resistor divider (1:2 scale)
- 🧠 Suitable for battery-powered IoT applications

---

## 🧠 Why Use 220kΩ Resistors?

The **220kΩ + 220kΩ** resistor pair forms a **simple 1:2 voltage divider**, reducing the input voltage by half before reaching the ADC. This allows the ESP32-C6 (which supports ~3.3V max on ADC) to safely measure up to ~6.6V input — perfect for single-cell Li-ion battery monitoring.

> ✅ High resistance = low current draw = battery friendly!

---


