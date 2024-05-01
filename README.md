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

## Flowchart
![Refernce Circuit](https://github.com/athulp1/SENSOR_HUB-IoT-miniproject/blob/main/a2.png)

- The flowchart illustrates the process of data collection and transmission in our project. Starting with the ESP32 microcontroller, which serves as the central hub, data is gathered from three sensors: MQ5 for air quality, DHT11 for temperature and humidity, and LDR for light levels.

- Each sensor provides specific environmental data: MQ5 measures air quality, DHT11 monitors temperature and humidity, while LDR gauges light intensity.

- These sensor readings are then communicated to the Serial Monitor for real-time observation and debugging if needed. Simultaneously, the data is transmitted to Google Firebase for secure storage and further analysis.

- This flowchart showcases the seamless flow of data from sensors to the ESP32, and then onwards to both the Serial Monitor and Google Firebase, ensuring efficient monitoring and management of environmental conditions.


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

## Results
The desired objective has been successfully achieved: the Sensor Hub's envisioned product now accurately presents temperature and humidity readings, as well as air quality (pollution) levels and light intensity. Moreover, all this valuable data is securely stored in the cloud, ensuring accessibility and reliability for users.

