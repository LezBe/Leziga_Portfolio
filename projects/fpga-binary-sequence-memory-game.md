---
layout: project
type: project
title: "FPGA Binary Sequence Memory Game"
date: 2026
published: true
projecturl: "https://github.com/LezBe/FPGA-Binary-Sequence-Memory-Game"
labels:
  - FPGA
  - Verilog
  - Digital Design
  - ModelSim
  - Quartus
summary: "Verilog FPGA memory game with hardware authentication, LFSR-based sequence generation, countdown timing, score tracking, and DE0-CV integration."
---

## FPGA Binary Sequence Memory Game

This project implemented a single-player binary sequence memory game in Verilog HDL on a Terasic DE0-CV Cyclone V FPGA.

The design combines multi-stage ID and password authentication, pseudo-random sequence generation, configurable countdown timing, personal and global score tracking using on-chip memory, finite-state-machine control, and seven-segment/LED feedback.

### Highlights

- Designed a modular Verilog RTL architecture for the DE0-CV FPGA
- Implemented ID and password authentication using ROM-backed lookup logic
- Developed FSM-based access control and gameplay sequencing
- Integrated a 16-bit LFSR-based pseudo-random generator for 4-bit game values
- Stored and evaluated an 8-value sequence during gameplay
- Implemented configurable countdown settings of 99, 66, 33, and 11 seconds
- Added personal-best and global-best score tracking using on-chip RAM
- Used button-shaping logic to convert physical button presses into single-cycle control pulses
- Verified core modules individually in ModelSim
- Demonstrated authentication, level selection, countdown timing, and player display on the DE0-CV hardware
- Identified the remaining board-level integration issue in the random-sequence display path

The final implementation reached complete module-level verification and partial hardware bring-up, with the sequence-display routing remaining as the primary integration issue.

[View the complete source code and technical documentation on GitHub](https://github.com/LezBe/FPGA-Binary-Sequence-Memory-Game).
