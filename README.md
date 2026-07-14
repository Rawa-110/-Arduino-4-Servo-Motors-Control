# -Arduino-4-Servo-Motors-Control
# Arduino 4 Servo Motors Control

## Project Overview

This project demonstrates how to control four servo motors simultaneously using an Arduino Uno and the Arduino Servo library. The goal is to make all four servo motors perform a sweep motion for 2 seconds and then stop at a fixed angle of 90 degrees.

This project is suitable for beginners who want to learn how to connect and program multiple servo motors using Arduino.

---

## Objectives

- Control four servo motors with a single Arduino Uno.
- Perform a synchronized sweep movement from 0° to 180° and back.
- Run the sweep motion for exactly 2 seconds.
- Stop all servo motors at 90° after the movement.
- Demonstrate the use of the Arduino Servo library.

---

## Components Used

- Arduino Uno R3
- 4 × Micro Servo Motors (SG90)
- Jumper Wires
- USB Cable
- Tinkercad Circuits (Simulation)

---

## Circuit Connections

### Servo 1
- Signal → Digital Pin D3
- VCC → 5V
- GND → GND

### Servo 2
- Signal → Digital Pin D5
- VCC → 5V
- GND → GND

### Servo 3
- Signal → Digital Pin D6
- VCC → 5V
- GND → GND

### Servo 4
- Signal → Digital Pin D9
- VCC → 5V
- GND → GND

All servo motors share the same 5V power supply and GND connection from the Arduino.

---
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7c56daa5-452e-434d-880d-0dbd9ee59039" />


## Software

- Arduino IDE
- Arduino Servo Library
- Tinkercad Circuits

---

## How the Program Works

1. The Servo library is included.
2. Four servo objects are created.
3. Each servo is attached to a different digital pin.
4. The program starts a timer using the `millis()` function.
5. All four servos sweep together from 0° to 180°.
6. The servos then return from 180° back to 0°.
7. The sweep continues until 2 seconds have elapsed.
8. Finally, all four servos move to 90° and remain there.

---

## Expected Output

- All four servo motors move together.
- The sweep motion lasts for approximately 2 seconds.
- After 2 seconds, every servo motor stops at 90 degrees.
- The motors remain at 90° until the Arduino is reset.

---

## Applications

This project can be used in many robotics and automation applications, including:

- Robotic arms
- Automated gates
- Robot joints
- Camera pan/tilt systems
- Educational robotics projects

---

## Learning Outcomes

By completing this project, the following skills are learned:

- Connecting multiple servo motors to Arduino.
- Using the Servo library.
- Programming synchronized motor movement.
- Controlling timing using `millis()`.
- Building and testing circuits in Tinkercad.

---

## Conclusion

This project demonstrates how to control four servo motors using an Arduino Uno and the Servo library. The simulation successfully performs a synchronized sweep motion for 2 seconds, after which all servo motors stop and hold at a 90-degree position.

The project provides practical experience in circuit design, servo motor control, Arduino programming, and simulation using Tinkercad. It serves as a strong foundation for developing more advanced robotics and automation projects.



Course: Arduino Programming

Platform: Tinkercad Circuits
