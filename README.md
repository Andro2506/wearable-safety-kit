Project Overview
This project implements a safety monitoring system that collects data related to environmental conditions (temperature and humidity) and physiological data (pulse rate) using sensors. It also incorporates GPS tracking to provide the user's location in case of emergencies. The system is designed to alert designated contacts via email in case of abnormal physiological readings.

Components Used
Microcontroller: ESP32
Sensors:
DHT11 for temperature and humidity sensing
MAX30105 for pulse rate monitoring
GPS module for location tracking
Other Modules:
Blynk for IoT connectivity and data visualization
EMailSender library for sending email alerts
Setup and Configuration
Connections: Ensure proper wiring of sensors and modules to the ESP32 microcontroller as specified in the code comments.
Software Dependencies: Install required libraries:
TinyGPS++
DHT sensor library
MAX30105 library
Blynk library
EMailSender library
Blynk Configuration: Replace placeholders with actual Blynk authentication token and WiFi credentials in the code.
Email Configuration: Update the sender's email credentials in the sendEmail() function.
Upload Code: Upload the provided code to the ESP32 microcontroller using the Arduino IDE or any other compatible development environment.
Usage
Power On: Power on the ESP32 microcontroller.
Data Monitoring: Real-time data related to temperature, humidity, pulse rate, and GPS location can be monitored through the Blynk mobile application or web dashboard.
Abnormal Condition Alert: If abnormal physiological readings (e.g., high pulse rate) are detected, an email alert containing the user's GPS location will be sent to the designated contact.
