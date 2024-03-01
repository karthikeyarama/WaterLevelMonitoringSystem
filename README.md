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

## Introduction

In urban areas, monitoring the water level in rooftop tanks can be challenging, leading to water wastage due to overflow. The Water Monitoring System presented here addresses this issue by providing users with real-time information about the water level in their tanks. By utilizing an ultrasonic sensor placed atop the tank, the system measures the distance to the water surface, enabling users to monitor the water level remotely.

## System Description

### Block Diagram

![image](https://github.com/karthikeyarama/WaterLevelMonitoringSystem/assets/93872893/47d6f1f5-f29e-4653-826b-59d4c92c8469)


## Hardware & Software Tools

### Hardware:
- **ESP32 DEVKIT V1**: A microcontroller board featuring Wi-Fi, Bluetooth, and other functionalities.
  - Operating Voltage: 3.3V
  - Input Voltage: 7-12V
  - Digital I/O Pins: 25
  - Analog Input Pins: 6
  - Flash Memory: 4 MB
  - SRAM: 520 KB
 
![image](https://github.com/karthikeyarama/WaterLevelMonitoringSystem/assets/93872893/c1af6f00-de3b-4547-b46d-3881dded1945)

- **Ultrasonic Sensor (HC-SR04)**: An electronic device for measuring distance based on ultrasonic waves.
  - Measurement Range: 2cm to 400cm
  - Accuracy: Up to 3mm
 

  ![image](https://github.com/karthikeyarama/WaterLevelMonitoringSystem/assets/93872893/da41bc86-0ddf-4d28-8f72-3b1727cd4ba6)


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
![image](https://github.com/karthikeyarama/WaterLevelMonitoringSystem/assets/93872893/922f5d25-d74d-42b0-bc26-59e4b0a440b6)
![image](https://github.com/karthikeyarama/WaterLevelMonitoringSystem/assets/93872893/7c4e1990-bfdc-41b3-aeb6-6365a37e5f43)
![image](https://github.com/karthikeyarama/WaterLevelMonitoringSystem/assets/93872893/ea40bb24-47a6-4b82-9092-beb612cd3a05)
![image](https://github.com/karthikeyarama/WaterLevelMonitoringSystem/assets/93872893/723cf724-4147-43be-afcf-2ede171c2894)
![image](https://github.com/karthikeyarama/WaterLevelMonitoringSystem/assets/93872893/0a606ff8-bb7b-43ea-abec-3183d3d66acb)
![image](https://github.com/karthikeyarama/WaterLevelMonitoringSystem/assets/93872893/cb7bb72e-38aa-475e-b5ac-c41b5b5f913f)
![image](https://github.com/karthikeyarama/WaterLevelMonitoringSystem/assets/93872893/1aa84731-4ed2-4d0f-8acb-7bfe31d5b179)


## Conclusion

The project demonstrates the use of ultrasonic sensors and IoT platforms for efficient water level monitoring. By providing users with remote access to water level data, the system contributes to water conservation efforts and reduces the manual effort required for monitoring tank levels.
