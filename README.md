# Arduino Obstacle Avoiding Car - README

# Project Overview
This project is a DIY obstacle-avoiding car built using Arduino that autonomously navigates while avoiding obstacles using an ultrasonic sensor.

# Components Required

# Electronics:
- **Arduino Board** (Uno or similar)
- **Motor Driver Shield** (compatible with AFMotor library)
- **4x DC Motors** with wheels
- **Servo Motor**
- **Ultrasonic Sensor** (HC-SR04)
- **Battery Pack** (suitable for motors)
- **Power Switch**
- **Jumper Wires**

# Mechanical:
- **Car Chassis** (to mount all components)
- **Wheels** (4 units)
- **Servo Mount** (to attach ultrasonic sensor)

# Wiring Connections

# Motor Connections:
- **Motor 1** → Motor Driver Port 1
- **Motor 2** → Motor Driver Port 2  
- **Motor 3** → Motor Driver Port 3
- **Motor 4** → Motor Driver Port 4

# Sensor Connections:
- **Ultrasonic Sensor:**
  - TRIG Pin → Arduino Pin A0
  - ECHO Pin → Arduino Pin A1
  - VCC → 5V
  - GND → GND

# Servo Connection:
- **Servo Signal** → Arduino Pin 10
- **Servo VCC** → 5V
- **Servo GND** → GND

# Code Setup

# Required Libraries:
1. **AFMotor.h** - For motor control
2. **NewPing.h** - For ultrasonic sensor
3. **Servo.h** - For servo motor control

# Installation Steps:
1. Install the required libraries in your Arduino IDE
2. Connect Arduino to computer via USB
3. Select correct board and port in Arduino IDE
4. Upload the provided code
