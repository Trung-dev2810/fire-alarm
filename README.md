# IoT-Based Gas Leak and Fire Detection System

This project aims to design a gas leak and fire detection system using an MQ2 sensor, STM32 microcontroller, and ESP8266 WiFi module to alert users both locally and remotely via a Web Server.

---

## Objectives

- Detect flammable and toxic gases: LPG, Methane, Alcohol, CO...
- Display gas levels and alerts on an LCD screen.
- Transmit real-time data to a Web Server via WiFi.
- Use STM32F103C8T6 microcontroller with UART and ADC interfaces.

---

## System Overview

### Main Functional Blocks:

- **MQ2 Gas Sensor** – detects gas concentrations.
- **STM32F103C8T6 MCU** – processes sensor data and controls output.
- **ESP8266-01 WiFi Module** – sends data to the cloud (ThingsBoard server).
- **LCD1602 Display** – visualizes sensor values and alerts.
