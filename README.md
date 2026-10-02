IoT Based Environmental Monitoring System

📌 Project Overview

This project is an IoT-based Environmental Monitoring System that monitors temperature and humidity in real time.

- DHT11 sensor senses temperature and humidity.
- STM32 reads and processes the sensor data.
- ESP8266 sends the data to the cloud through Wi-Fi.
- ThingSpeak is used to monitor the sensor values remotely in real time.

🔧 Components Used

- STM32 Microcontroller
- DHT11 Temperature & Humidity Sensor
- ESP8266 Wi-Fi Module
- ThingSpeak Cloud Platform

⚙️ Working

DHT11 → STM32 → ESP8266 → Wi-Fi → ThingSpeak

The DHT11 sensor collects temperature and humidity data. STM32 reads and processes the sensor data. The ESP8266 sends the processed data to ThingSpeak through Wi-Fi, where the values can be monitored remotely.

💻 Software Used

- STM32CubeIDE
- Arduino IDE
- ThingSpeak
- Embedded C

🎯 Key Features

- Real-time temperature monitoring
- Real-time humidity monitoring
- Wireless data transmission
- Remote monitoring through ThingSpeak
