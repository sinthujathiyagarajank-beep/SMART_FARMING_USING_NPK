🌱 Smart Farming System Using NPK Sensor (IoT)

This project implements an IoT-based smart farming monitoring system using ESP8266 (NodeMCU) to measure and display real-time soil nutrient and environmental parameters. The system helps monitor soil health by collecting data from multiple sensors and presenting it locally on an LCD and remotely through a web interface.

🔧 Features

Real-time monitoring of Nitrogen (N), Phosphorous (P), and Potassium (K) using an NPK sensor

Measurement of soil moisture, temperature, and humidity

ESP8266 Wi-Fi connectivity for hosting a live web dashboard

Local display of sensor values on a 16×2 I2C LCD

Simple and lightweight HTTP web server for browser-based monitoring

🧠 Working Principle

The ESP8266 reads environmental data from the DHT11 and soil moisture sensor, while NPK values are obtained via RS485 Modbus RTU communication. All sensor readings are processed in real time and displayed simultaneously on an LCD and a web page that refreshes automatically.

🛠 Hardware Used

ESP8266 (NodeMCU)

NPK Soil Nutrient Sensor (RS485 – Modbus RTU)

Soil Moisture Sensor

DHT11 Temperature & Humidity Sensor

16×2 I2C LCD

💻 Software & Tools

Embedded C

Arduino IDE

ESP8266 Wi-Fi Library

Modbus RTU communication

🎯 Applications

Soil nutrient monitoring

Smart agriculture and precision farming

Educational IoT and embedded systems projects

🚀 Future Enhancements

Cloud data logging and visualization

Mobile application integration

Automated irrigation and fertilizer control

If you want, I can also:

Write a short GitHub repo description (1–2 lines)

Add README badges + folder structure

Clean and comment your code for public viewing

Just tell me 👍
