---
layout: project
type: project
title: "Go Baby Go — Accessible Ride-On Vehicle Control System"
date: 2025
published: true
labels:
  - Embedded Systems
  - Motor Control
  - Circuit Design
  - Power Electronics
  - Assistive Technology
summary: "Team design of an accessible electric ride-on vehicle, integrating Arduino-based motor controls, optocoupler-interfaced start/stop inputs, a dual-channel motor driver, and regulated power distribution."
---

## Go Baby Go — Accessible Ride-On Vehicle Control System

**Go Baby Go** is an assistive-technology initiative that adapts ride-on vehicles for children with mobility impairments. As part of a University of Houston Biomedical Engineering Society team project (2024–2025), the team developed an electrical and control-system design intended to make a modified vehicle easier to operate while prioritizing safe motor behavior.

### Electrical and Control Architecture

The documented design includes:

- **Arduino Mega** to interpret console inputs and issue motor and steering commands
- **RoboClaw 2x60A dual-channel motor driver** interfacing with two geared DC drive motors
- **12 V battery** supplying the motor driver and auxiliary power-conversion system; the documented drive motors are rated at 24 V
- **DC-DC buck converter** to support lower-voltage electronics, including steering hardware
- **4N35 optocouplers** specified on the start/stop button input interfaces to the Arduino
- **PWM and direction control** for motor speed and direction, alongside a steering input
- **40 A inline fuse** specified for battery-side circuit protection

### Design Goals and Engineering Considerations

- Targeted a **1–3 mph** operating speed range with stepped speed selection
- Specified a dedicated **stop** input intended to halt vehicle movement
- Considered forward/reverse switching, steering limits, power distribution, and thermal management
- Integrated control-input interfacing with motor-driver and steering-system planning

### My Work

My work included developing the **optocoupler-based isolation approach and supporting motor-control/power circuitry**, with an emphasis on safe subsystem interfacing and system integration. The technical design connects the start/stop controls to Arduino digital inputs through optocoupler circuitry; this is **control-input isolation**, not evidence that the entire motor supply was galvanically isolated.

### Documentation and Verification Status

This project was collaborative. The technical document and meeting reports describe component selection, circuit diagrams, wiring plans, early power/motor setup, and intended testing procedures. A February 2025 meeting report records completion of initial power and motor setup, along with buck-converter voltage adjustment tests.

**Design targets are not presented as measured outcomes.** In particular, the available records do not establish a measured noise reduction, proven isolation withstand voltage, or verified long-term reliability improvement. Those claims require additional test data.

*Project documentation: Go Baby Go Technical Document (2024–2025) and project meeting records. The shared team Drive folder is intentionally not linked publicly.*
