# Water Monitoring System using ESP32 and Ultrasonic Sensor (HC-SR04)

This repository contains the project documentation and code for a Water Monitoring System developed as part of the course on Fundamentals of IoT. The system aims to address the issue of water wastage by providing real-time monitoring of water levels in tanks using an ESP32 microcontroller and an ultrasonic sensor (HC-SR04). The system utilizes the Blynk IoT platform to provide users with a convenient interface for monitoring water levels remotely via a mobile application.

## Table of Contents

1. [Introduction](#introduction)
2. [System Description](#system-description)
   - [Block Diagram](#block-diagram)
3. [Hardware & Software Tools](#hardware-and-software-tools)
4. [Implementation](#implementation)
5. [Results](#results)
6. [Conclusion](#conclusion)
7. [References](#references)

## Introduction

In urban areas, monitoring the water level in rooftop tanks can be challenging, leading to water wastage due to overflow. The Water Monitoring System presented here addresses this issue by providing users with real-time information about the water level in their tanks. By utilizing an ultrasonic sensor placed atop the tank, the system measures the distance to the water surface, enabling users to monitor the water level remotely.

## System Description

### Block Diagram

[Add block diagram image here]

## Hardware & Software Tools

### Hardware:
- **ESP32 DEVKIT V1**: A microcontroller board featuring Wi-Fi, Bluetooth, and other functionalities.
  - Operating Voltage: 3.3V
  - Input Voltage: 7-12V
  - Digital I/O Pins: 25
  - Analog Input Pins: 6
  - Flash Memory: 4 MB
  - SRAM: 520 KB
- **Ultrasonic Sensor (HC-SR04)**: An electronic device for measuring distance based on ultrasonic waves.
  - Measurement Range: 2cm to 400cm
  - Accuracy: Up to 3mm

### Software:
- **Blynk**: An IoT platform for controlling hardware remotely via smartphones.
- **Arduino IDE**: An open-source integrated development environment for programming microcontrollers.
  - Libraries: WiFi.h, WiFiClient.h, BlynkSimpleEsp32.h

## Implementation

The implementation of the Water Monitoring System involves the following steps:
1. Gather necessary components.
2. Establish connections between ESP32 and ultrasonic sensor.
3. Create an account on Blynk.io and set up a new project.
4. Configure datastreams and widgets in the Blynk project.
5. Integrate Blynk authentication tokens into the Arduino sketch.
6. Upload the sketch to the ESP32 microcontroller.

## Results

The Water Monitoring System provides users with real-time information about the water level in their tanks, accessible through the Blynk mobile application or web dashboard. This helps users prevent water wastage by avoiding overflow and allows for efficient monitoring of water usage.

## Conclusion

The project demonstrates the use of ultrasonic sensors and IoT platforms for efficient water level monitoring. By providing users with remote access to water level data, the system contributes to water conservation efforts and reduces the manual effort required for monitoring tank levels.
