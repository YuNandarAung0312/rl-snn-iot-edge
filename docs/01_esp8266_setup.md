# ESP8266 Setup

## 1. Install Arduino IDE

Download Arduino IDE from:

https://www.arduino.cc/en/software/

Install Arduino IDE for your operating system.

## 2. Add ESP8266 Board Support

Open:

Arduino IDE → Settings

Add the following URL to:

Additional Boards Manager URLs

https://arduino.esp8266.com/stable/package_esp8266com_index.json

## 3. Install ESP8266 Board Package

Open:

Tools → Board → Boards Manager

Search for:

ESP8266

Install:

esp8266 by ESP8266 Community

## 4. Select the Board

For a NodeMCU-style ESP8266:

Tools → Board → ESP8266 Boards → NodeMCU 1.0 (ESP-12E Module)

## 5. Select the Serial Port

Connect the ESP8266 using a USB data cable.

Open:

Tools → Port

Select the serial port corresponding to the ESP8266.

## 6. Install DHT Library

Open:

Tools → Manage Libraries

Search for:

DHT sensor library

Install:

DHT sensor library by Adafruit

Also install:

Adafruit Unified Sensor
