# IoT-Based Smart Agriculture Monitoring System

An IoT-based smart agriculture monitoring system for real-time monitoring of soil moisture and field activities using sensors, MQTT, MySQL, and Grafana.

## Project Overview

The system collects data from a Soil Moisture Sensor and IR Sensor using an ESP8266/ESP32 controller. The sensor data is transmitted through an MQTT Broker, stored in a MySQL database, and visualized using Grafana dashboards.

## Technologies Used

- ESP8266 / ESP32
- Soil Moisture Sensor
- IR Sensor
- Arduino IDE
- MQTT
- MySQL
- Grafana
- Python
- Wi-Fi

## Features

- Continuous soil moisture monitoring
- IR-based object/activity detection
- Real-time MQTT data transmission
- MySQL data storage
- Grafana dashboard visualization
- Real-time and historical monitoring

## System Architecture

```text
Soil Moisture Sensor + IR Sensor
                ↓
          ESP8266 / ESP32
                ↓
           MQTT Broker
                ↓
          MySQL Database
                ↓
        Grafana Dashboard
                ↓
      Farmer Monitoring System
