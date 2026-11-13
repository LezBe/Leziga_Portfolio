---
layout: project
type: project
title: "Avionics Sensor Board"
date: 2026
published: true
projecturl: "https://github.com/LezBe/Avionics-Sensor-Board"
labels:
  - PCB Design
  - KiCad
  - SPI
  - Avionics
  - Sensor Integration
summary: "Collaborative avionics sensor-board hardware with KiCad schematics, integrated PCB files, and planned SPI-based interfaces to a flight computer."
---

## Avionics Sensor Board

A collaborative avionics hardware project for a University of Houston rocketry team. The repository contains several sensor-circuit designs and an integrated KiCad board project for interfacing sensors with the flight computer.

### Engineering Scope

- Sensor interfaces and supporting circuitry in KiCad
- Shared SPI clock/data bus with separate chip-select lines in the documented architecture
- Board-level power distribution, footprint review, PCB integration and hardware bring-up planning
- Version-controlled schematic/PCB collaboration

### Public Design Evidence

These are **actual design files**, not illustrative screenshots:

- [BMP sensor schematic](https://github.com/LezBe/Avionics-Sensor-Board/blob/main/hardware/BMP_unit.kicad_sch)
- [LSM6DSO32 sensor design folder](https://github.com/LezBe/Avionics-Sensor-Board/tree/main/hardware/LSM6DSO32_schematic)
- [GPS board design folder](https://github.com/LezBe/Avionics-Sensor-Board/tree/main/hardware/GPS%20board)
- [Integrated ESP32 Sensor Hat PCB/schematic](https://github.com/LezBe/Avionics-Sensor-Board/tree/main/hardware/sensor_board)

### My Contributions

Contributed to avionics hardware development, including sensor-interface design and KiCad/Git-based integration workflows. Individual circuit ownership and test coverage should be clarified against the team's contribution history before asserting end-to-end ownership.

### Status

PCB and schematic source files are present on `main`. The published bring-up checklist is not signed off; there are no publicly documented measured performance results in the reviewed repository. Do not interpret file presence alone as manufacturing or flight qualification.

[Read the complete source and hardware documentation](https://github.com/LezBe/Avionics-Sensor-Board).
