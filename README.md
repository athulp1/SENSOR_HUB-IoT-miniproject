# SENSOR_HUB-IoT-miniproject

In today's world, the rampant industrialization, burgeoning population, and increasing consumerism have propelled environmental degradation to alarming levels. Pollution, in its myriad forms, poses a grave threat to our planet's well-being. To combat this pressing issue, we present SensorHUB — a pioneering solution designed to revolutionize IoT development and address the complexities of environmental monitoring.

## Features

- Sensor Integration: Connect temperature, humidity, pollution, and light level sensors to a central Sensor Hub.
- Data Logging: Implement periodic data logging from sensors to an IoT Cloud platform.
- Real-time Monitoring: Enable real-time monitoring of sensor data through the IoT Cloud interface.
-	Alert System: Implement an alert system in the IoT Cloud platform for abnormal sensor readings, ensuring prompt attention to critical environmental conditions.

## Final Design


Integrated Design:
ESP32 microcontroller board integrated with DHT11, MQ5, and LDR sensors on a single platform for seamless data collection and processing.
Multi-Sensor Capability:
Monitoring of temperature, humidity, gas concentrations, and light intensity using DHT11, MQ5, and LDR sensors respectively, offering comprehensive environmental insights.
Real-Time Monitoring:
Continuous monitoring of environmental parameters in real-time, providing instant updates on air quality, light levels, and potential gas emissions.
Proactive Environmental Management:
Timely data collection and analysis enable proactive strategies for environmental management, facilitating prompt responses to changing conditions and potential hazards.

## Hardware Design
-	Connect Sensors to ESP32: - Plug in temperature, humidity, pollution, and light level sensors to the ESP32 board and connect it to them
- Write Code to Read Data: - Using Arduino to tell ESP32 how to read information from each sensor
- Send Data to Cloud: - In your Arduino code, add instructions to send the recorded sensor data to your firebase cloud account
- Cloud Stores Your Data: - The google firebase cloud will store your data in a safe digital space

![Refernce Circuit](https://github.com/athulp1/SENSOR_HUB-IoT-miniproject/blob/main/a1.png)

Above Circuit image is just for reference.

## Arduino Code Setup

1. Install the Arduino IDE and required libraries.
2. Open the Arduino IDE and upload the provided SmartGlow_ESP8266.ino sketch to your NodeMCU ESP32.

