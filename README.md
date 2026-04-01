# ESP32 Multi-Sensor Monitoring System

## Overview
This project is an ESP32-based multi-sensor monitoring system designed to collect and analyze real-time data from multiple sensors.

## Features
- Pressure sensing
- Temperature and humidity monitoring
- IMU-based motion detection
- CAN communication
- Threshold-based anomaly detection

## Hardware Used
- ESP32
- KP467 pressure sensor
- BME280
- LSM6DSVXXX IMU
- SD card

## Software Used
- Arduino IDE
- C++
- MATLAB

## Communication Protocols
- SPI
- I2C
- CAN

## Project Structure
- `software/` contains the embedded code
- `hardware/` contains wiring and hardware documentation
- `images/` contains setup images
- `results/` contains output screenshots and plots

## Results
The system successfully monitored real-time sensor data and generated alerts based on threshold conditions. An SD card is used to log data, and a real-time monitoring system was implemented using a web-based dashboard.

## Future Improvements
- Improve anomaly detection using machine learning

