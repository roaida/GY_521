# GY-521 MPU6050 Module – Complete Documentation
This repository contains detailed documentation, schematics, notes, and practical usage for the **GY-521 module**, which is based on the **MPU6050** 6-axis motion sensor. Ideal for beginners, students, and hobbyists learning about motion sensing and I2C communication.

## About the GY-521 Module
The **GY-521** is a breakout board for the **MPU6050**, a 6-DOF motion tracking sensor that combines:
- 3-axis Accelerometer
- 3-axis Gyroscope
- I2C interface for digital communication
The module includes onboard support circuitry like voltage regulation, pull-up resistors, and a power LED.

## Features
- MPU6050 6-DOF Motion Sensor
- Built-in 3.3V Voltage Regulator (accepts 3.3V–5V input)
- I2C Communication (SDA/SCL)
- Power indicator LED
- Ready-to-use with Arduino, ESP32, STM32, and others

## Pinout
| GY-521 Pin | Description         |
|------------|---------------------|
| VCC        | Power Input (3.3V–5V) |
| GND        | Ground               |
| SDA        | I2C Data             |
| SCL        | I2C Clock            |
| XDA/XCL    | Auxiliary I2C        |
| AD0        | I2C Address Selector |
| INT        | Interrupt Output     |

## I2C Address
- Default: `0x68`
- Alternate: `0x69` (when AD0 pin is HIGH)

## Applications
- Self-balancing robots 🤖
- Drones & quadcopters 🚁
- Gesture & motion detection 🎮
- Wearables & fitness devices ⌚
- VR/AR systems 🕶️

## 📝 Included in This Repo
- ✅ Cleaned and labeled schematic diagram
- ✅ Complete technical breakdown of all components
- ✅ Block diagram for easy understanding
- ✅ Beginner-friendly explanations
- ✅ Application examples

Created and documented by Roaida Binta Ali

