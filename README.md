# TEMPERATURE-MONITORING-SYSTEM

NAME: RANGA DEEPSHIKA

COMPANY: CODTECH IT SOLUTIONS

INTERN ID: CT04DM585

DOMAIN: EMBEDDED SYSTEMS

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH



##  **Project Description**

The **Temperature Monitoring System using ESP32** is an Internet of Things (IoT)-based project designed to measure, monitor, and display temperature data in real-time. This system uses the **ESP32** microcontroller—a powerful, Wi-Fi and Bluetooth-enabled microcontroller—to read temperature from a sensor, process it, and display it on a **web interface**, **serial monitor**, or **LCD display**. The ESP32 is chosen for its low power consumption, integrated wireless capabilities, and dual-core performance, making it ideal for remote monitoring applications.

The core functionality of this system involves interfacing a **temperature sensor** (such as the DHT11, DHT22, or LM35) with the ESP32 to capture ambient temperature readings. The ESP32 reads the temperature data at regular intervals and displays it locally or transmits it over Wi-Fi to a web dashboard or mobile interface. This enables remote access to the environmental conditions of a room, greenhouse, server room, or any other monitored area.

The **DHT11/DHT22 sensor** is a popular choice due to its reliability, ease of use, and ability to provide both temperature and humidity readings. The data from the sensor is read through one of the ESP32’s GPIO pins and processed using libraries such as `DHT.h` in the Arduino IDE environment. The measured temperature is then output through various interfaces:

1. **Serial Monitor**: For local testing and debugging, the temperature values can be printed to the serial monitor at set intervals.
2. **LCD Display**: A 16x2 LCD or OLED can be used to show real-time values locally.
3. **Web Server**: The ESP32 can host a simple web server to serve an HTML page showing the temperature readings, allowing users to access the data from any browser on the same network.

The web interface can be further enhanced to display graphs, log historical data, or send alerts if temperatures cross predefined thresholds. These features make the system suitable for real-world applications like environmental monitoring, smart agriculture, server room temperature control, or home automation.

This project teaches how to:

* Interface sensors with the ESP32 microcontroller.
* Set up Wi-Fi communication and serve data over HTTP.
* Use Arduino IDE to program ESP32 with sensor libraries.
* Build basic IoT functionality for real-time monitoring.

The system is **modular and scalable**. More sensors can be added (e.g., humidity, pressure, CO₂ sensors), and data can be pushed to cloud platforms such as ThingSpeak, Blynk, or Firebase for global access and data logging. Additionally, using power-efficient features of the ESP32 like deep sleep modes can make it suitable for battery-operated and solar-powered applications.

---

## ✅ **Key Features**

* Real-time temperature measurement
* Wi-Fi-based monitoring via web browser
* Local display via LCD or OLED (optional)
* Low power, cost-effective, and scalable design
* Ideal for IoT and remote monitoring use cases

---
#OUTPUT

![Image](https://github.com/user-attachments/assets/0f0c8ad1-fe4d-4a72-b422-72a6a26d5fac)

