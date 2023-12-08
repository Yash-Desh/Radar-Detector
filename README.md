**Course Name: Electronic Engineering Practice (R4EC3007L)**

**Date: July-December 2022**


# Radar Detector

An Arduino based radar to detect and pinpoint objects in vicinity.

## Table of Contents

- [About the Project](#about-the-project)
    - [Aim](#aim)
    - [Description](#description)
- [Getting Started](#getting-started)
    - [Components](#components)
    - [Tech Stack](#tech-stack)
    - [Software](#software)
- [Theory and Approach](#theory-and-approach)
- [Contributors](#contributors)
- [Acknowledgements and Resources](#acknowledgements-and-resources)

## About The Project

### Aim

Develop an Arduino UNO based Ultrasonic Radar Detector to provide a versatile and cost-effective solution to enhance proximity sensing and obstacle detection, 

### Description
The aim of the Arduino-based Ultrasonic Radar Detector project is to develop an efficient and cost-effective radar system that utilizes ultrasonic sensors and Arduino microcontroller for accurate distance measurement and obstacle detection. This project aims to leverage the capabilities of ultrasonic technology to create a versatile radar system suitable for applications such as parking assistance, obstacle avoidance in robotics, and real-time distance monitoring. Through the integration of Arduino, the project seeks to provide a customizable and user-friendly solution, enabling enthusiasts and developers to explore and implement ultrasonic radar technology for diverse purposes.


## Getting Started

### Components

- Arduino UNO Board 
- SG90 Servo motor 
- HC-SR04 Ultrasonic sensor
- Bread board
- Jumper wires

### Tech Stack
- Processing Java
- C++

### Software
- [Tinkercad](https://www.tinkercad.com/)  
- [Arduino IDE](https://www.arduino.cc/en/main/software)
- [Processing](https://processing.org/download/support.html)

## Theory and Approach

## Build process

#### 1. Connect the HC-SR04 to Arduino:

- Attach the VCC pin of the HC-SR04 to the 5V output on the Arduino.
- Connect the GND pin of the HC-SR04 to the GND on the Arduino.
- Connect the Trig pin of the HC-SR04 to a digital pin on the Arduino (e.g., pin 2).
- Connect the Echo pin of the HC-SR04 to another digital pin on the Arduino (e.g., pin 3).

####  2. Attaching a Servo Motor:

- Use a servo motor for a rotating radar effect, connect the red wire to the 5V output on the Arduino.
- Connect the brown wire of the servo to the GND on the Arduino.
- Connect the orange/yellow wire of the servo to a digital PWM pin on the Arduino (e.g., pin 9).

![Picture7](https://github.com/Yash-Desh/Radar-Detector/assets/84829056/b9be3416-bfde-499d-8212-655d1a2b6be9)


#### 3. Code for the Arduino:

The program in the Arduino IDE that reads data from the HC-SR04 sensor and controls the servo motor. The code includes functions to trigger the ultrasonic pulse, measure the echo duration, calculate distance, and control the servo motor based on the detected distance.
For the Processing code, pressing the Run button will show a processing window. It will show both servo angle of the radar and the object distance.

#### 4. Uploading the Code:

- Connect the Arduino to your computer using a USB cable.
- Open the Arduino IDE, use the given code, select the correct board (Arduino UNO), and upload the code to the Arduino.
- Similarly, open Processing IDE, select the correct board (Arduino UNO), and upload the provided code.

#### 5. Test and Calibrate:

- Power up the Arduino and observe the behavior. Use the Processing window to view distance readings and troubleshoot any issues.
- Adjust the servo motor positions and distance thresholds in the code to optimize the radar detector's performance.
- Physically mount the HC-SR04 and, if applicable, the servo motor on a stable platform to create a scanning effect.

## Working

-	The ultrasonic sensors are mounted on a rotating platform, allowing for a 180-degree field of view. 
-	The Arduino microcontroller is responsible for receiving the sensor data and processing it in real-time. 
-	It then sends this data to a connected computer running the Processing software, which displays the results in a user-friendly interface.
-	On the Processing software interface, the detected object is shown on the screen with an estimate of its closeness.
-	The red lines on the screen indicate the detected object.
-	The distance of the object from the sensor is indicated by the length of the red lines

![Picture1](https://github.com/Yash-Desh/Radar-Detector/assets/84829056/571a6572-3815-44c5-810f-0bcf3e03477c)




## Results and Demo
The result of this was a Radar system utilizing Arduino and ultrasonic sensors that provides a reliable and accurate method for detecting objects within a specified range.

![Picture6](https://github.com/Yash-Desh/Radar-Detector/assets/84829056/065e71ba-7d0b-417a-9402-ea673f7de36b)



## Contributors

- [Yash Deshpande](https://github.com/yashLM705)
- [Pratik Kardile](https://github.com/Aerophile-320)
- [Atharva Apkare](https://github.com/atharvaapkare)
- Milind Jha

## Acknowledgements and Resources

- [Instructables Arduino Radar](https://www.instructables.com/Arduino-Radar-1/l)
- [Arduino Project Hub : Ultrasonic Radar with Arduino](https://projecthub.arduino.cc/nimishac/ultrasonic-radar-with-arduino-19baa3)
- [Indian LifeHacker Video Tutorial](https://youtu.be/JvmIutmQd9U?si=GWHuDyaTuALvH80Y)
