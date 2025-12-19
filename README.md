# Automatic-door-opening-system-using-esp32
# IoT-Based Automatic Door Opening System Using ESP32

## Project Overview
This project demonstrates a **smart automatic door system** using an ESP32 microcontroller and an ultrasonic sensor. The system detects a person approaching and automatically opens or closes the door using a servo motor. It is an **IoT-ready prototype** that can be extended for remote monitoring and control.

## Components Used
- ESP32 Microcontroller
- Ultrasonic Sensor (HC-SR04)
- Servo Motor
- Jumper Wires
- Power Supply
- Door Structure / Mounting Setup

## Features
- Detects presence using ultrasonic sensor
- Automatic door opening and closing
- Servo motor control for smooth operation
- IoT-ready system with potential for Wi-Fi integration

## How It Works
1. The **ultrasonic sensor** detects the distance of an object/person.
2. When an object comes within a certain range, the ESP32 sends a signal to the **servo motor**.
3. The servo motor rotates to open the door automatically.
4. When the object moves away, the door closes automatically.


## How to Run
1. Open `automatic_door_esp32.ino` in Arduino IDE.
2. Select **ESP32 board** and correct **COM port**.
3. Upload the code to ESP32.
4. Power the ESP32 and observe automatic door operation.

## Future Improvements
- Add Wi-Fi connectivity for **remote monitoring**
- Integrate a **mobile app** for control
- Add a **security feature** like RFID or face recognition

## Author
**Malik Muhammad Abdul Rafay**  
Student of Mechtronics Engineering

