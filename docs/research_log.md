# Research Log

This document records the development process, experiments,
problems, solutions, and observations for the RL-SNN-IoT project.

---

## 2026-08-26 — Project Setup

### Objective

Develop an IoT sensing and edge-AI platform using:

DHT11 → ESP8266 → Wi-Fi → MQTT → Raspberry Pi

The long-term objective is to investigate reinforcement
learning-based optimization of spiking neural networks
for resource-constrained IoT edge devices.

### Hardware

- ESP8266
- DHT11 temperature and humidity sensor
- Raspberry Pi 3B

### Software

- Arduino IDE
- ESP8266 Arduino core
- Adafruit DHT Sensor Library

### Progress

- Installed Arduino IDE.
- Installed ESP8266 board support.
- Installed DHT Sensor Library.
- Connected DHT11 to ESP8266.
- Successfully obtained temperature and humidity readings.

### Problem Encountered

Initially configured the sensor as DHT22, although the actual
sensor was DHT11.

### Solution

Changed the sensor configuration from DHT22 to DHT11.

### Current Status

DHT11 → ESP8266 → Serial Monitor: SUCCESS

### Next Step

Connect ESP8266 to Wi-Fi and establish communication with
the Raspberry Pi using MQTT.
