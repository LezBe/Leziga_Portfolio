---
layout: project
type: project
title: "Autonomous Navigation & Control Robot"
date: 2025
published: true
projecturl: "https://github.com/LezBe/Autonomous-Navigation-Control-Robot"
labels:
  - Embedded Systems
  - TI-RTOS
  - Robotics
  - C
  - Control Systems
summary: "Autonomous Tiva C robot using TI-RTOS, IR sensing, PWM motor control, real-time event handling, and wall-following control."
---

## Autonomous Navigation & Control Robot

This project integrated embedded control, sensing, motor actuation, communication, and real-time event handling on a TI TM4C123GXL Tiva C microcontroller.

The robot used front and right-side IR distance sensors to navigate autonomously, maintain its position relative to a wall, react to obstacles, and execute turning behavior. Motor speed was controlled using PWM, while TI-RTOS hardware interrupts, software interrupts, and a background task coordinated sensor acquisition, wall-following control, line events, and data logging.

### Highlights

- Implemented a 50 ms wall-following control loop
- Used 20 kHz PWM for independent left/right motor control
- Maintained approximately ±1 cm wall-tracking accuracy
- Integrated ADC-based IR distance sensing
- Implemented UART communication over USB and an HC-05 Bluetooth module
- Used a 2 × 20 ping-pong buffer for control-error logging
- Integrated line-sensor events with LED feedback and a one-minute shutdown sequence

[View the complete source code and technical documentation on GitHub](https://github.com/LezBe/Autonomous-Navigation-Control-Robot).
