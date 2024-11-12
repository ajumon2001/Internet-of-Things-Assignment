# IoT Environmental Monitoring System

This repository contains code and documentation for an IoT-based environmental monitoring system. This project collects temperature and humidity data using an ESP32 microcontroller, DHT sensor, and publishes data to a cloud-based NoSQL database via MQTT using Node-RED. The system allows real-time data monitoring and storage for analytics and historical analysis.

## Project Overview

- **Device**: ESP32 Microcontroller
- **Sensors**: DHT11 for temperature and humidity measurement
- **Communication Protocol**: MQTT
- **Data Processing**: Node-RED
- **Data Storage**: MongoDB (NoSQL database)
- **Data Visualization**: Node-RED Dashboard

## Features

- Real-time temperature and humidity data collection.
- Cloud storage using MongoDB for time-series data analysis.
- LED-based visual feedback on temperature thresholds.
- Configurable publish interval and manual LED control via MQTT.
- JSON data formatting with timestamping for structured storage and easy retrieval.

## Project Structure


## Getting Started

### Prerequisites

1. **Hardware**:
   - ESP32 microcontroller
   - DHT11 or DHT22 sensor
   - RGB LED (optional, for visual feedback)

2. **Software**:
   - Arduino IDE or PlatformIO (for ESP32 programming)
   - Node-RED (for data processing and visualization)
   - MongoDB (for data storage, recommended to use MongoDB Atlas for cloud storage)

### Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/IoT-Environmental-Monitoring.git
   cd IoT-Environmental-Monitoring  
