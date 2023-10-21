# Smart Lab and Smart Stairs IoT Project

![Smart Lab and Smart Stairs](images/project_image.jpg)

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Hardware Components](#hardware-components)
- [Installation](#installation)
- [Usage](#usage)
- [Mobile App](#mobile-app)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The **Smart Lab and Smart Stairs** project is an innovative IoT (Internet of Things) solution that combines Arduino Uno and a variety of sensors to create a smart environment for both laboratories and staircases. This project leverages the power of automation and sensor technology to enhance safety, energy efficiency, and convenience in these spaces.

### Smart Stairs

The Smart Stairs component of the project is designed to automatically detect the presence of a person on the staircase and control the lighting accordingly. It utilizes ultrasonic and infrared (IR) sensors to detect the presence of individuals, enabling energy-efficient lighting control.

### Smart Lab

The Smart Lab component focuses on creating an intelligent and secure environment within the lab. It employs a range of sensors to detect the presence of people and environmental conditions, such as temperature and humidity. Additionally, it incorporates a fire detection system for added safety. When no movement is detected, the lights are automatically turned off, saving energy. In case of rising temperatures, a DC fan acts as an exhaust to regulate the environment. The project also includes an alarm system to detect and respond to the presence of smoke or fire using the MQ-2 smoke sensor.

## Features

- **Smart Stairs**:
  - Automatic lighting control based on presence detection using ultrasonic and IR sensors.
- **Smart Lab**:
  - Automated lighting control within the lab based on occupancy.
  - Real-time monitoring of temperature and humidity.
  - Smoke and fire detection with alarm system.
  - Energy-saving feature: lights turned off when no movement is detected.
  - Temperature-regulated DC fan for climate control.
- **Mobile App**:
  - Bluetooth-based mobile app for remote monitoring and control of the system.

## Hardware Components

To build the Smart Lab and Smart Stairs project, you will need the following hardware components:

- Arduino Uno
- Ultrasonic Sensor
- Infrared (IR) Sensor
- Passive Infrared (PIR) Sensor
- MQ-2 Smoke Sensor
- Buzzer
- 5V DC Fan
- HC-05 Bluetooth Module
- LCD Display
- Temperature and Humidity Sensor

## Installation

1. Assemble the hardware components as per the provided schematics or your own design.

2. Upload the Arduino code to the Arduino Uno board for both the Smart Lab and Smart Stairs components. The code for each component can be found in their respective directories.

3. Power up the system and ensure all sensors and components are connected correctly.

4. The mobile app can be installed on your Android device. Pair your device with the HC-05 Bluetooth module to control and monitor the system remotely.

## Usage

### Smart Stairs

1. Place the ultrasonic and IR sensors in the appropriate positions on the staircase.

2. When a person approaches the stairs, the lighting will automatically turn on, and it will turn off when no motion is detected.

### Smart Lab

1. Set up the sensors as required in the lab, including the PIR sensor, MQ-2 smoke sensor, temperature, and humidity sensor.

2. The system will automatically control the lighting, fan, and alert you in case of smoke or fire detection.

3. The LCD display will show real-time temperature and humidity information.

4. When no movement is detected, the lights will be turned off to save energy. The DC fan will operate to regulate the temperature if it rises.

## Mobile App

The mobile app allows you to monitor and control the Smart Lab and Smart Stairs system remotely. Simply connect your Android device to the HC-05 Bluetooth module and use the app to:

- Check the status of lights, fan, and sensors.
- Turn the lights and fan on/off.
- Receive notifications in case of fire or smoke detection.

## Contributing

We welcome contributions from the open-source community. If you have ideas for improvements, bug fixes, or new features, feel free to create a pull request.

## License

This project is open-source and licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this software as per the terms of the license.
