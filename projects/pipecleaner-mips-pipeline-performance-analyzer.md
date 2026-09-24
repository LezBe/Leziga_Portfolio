---
layout: project
type: project
title: "PipeCleaner — MIPS Pipeline Performance Analyzer"
date: 2026
published: true
projecturl: "https://github.com/zoeyeballard/PipeCleaner"
labels:
  - Computer Architecture
  - Python
  - MIPS
  - Pipelining
  - Hazard Detection
summary: "Collaborative Python-based MIPS performance analyzer comparing single-cycle and 5-stage pipelined execution, with my contribution focused on hazard detection, stalls, flushes, and forwarding logic."
---

## PipeCleaner — MIPS Pipeline Performance Analyzer

PipeCleaner is a collaborative computer architecture project developed for ECE 5367. The Python-based analyzer compares single-cycle processor timing against a 5-stage pipelined MIPS architecture using assembly or machine-code workloads.

The project parses a supported subset of MIPS instructions and reports performance metrics including CPI, execution time, latency, throughput, pipeline stalls, and instruction hazards.

### My Contribution

My primary responsibility was the pipeline hazard detection and forwarding module (`person5_hazard.py`).

- Developed cycle-level hazard detection logic for the 5-stage pipeline
- Implemented load-use stall detection and pipeline bubble decisions
- Implemented control-hazard flush logic for branch handling
- Developed EX/MEM and MEM/WB data-forwarding decisions for ALU operands
- Added static register dependency analysis for RAW hazard detection
- Implemented analytical counting of RAW hazards, branch instructions, and required stall cycles
- Integrated hazard information with the project's broader pipeline performance-analysis workflow
- Contributed to integration, debugging, and final project refinement alongside the development team

### Project Capabilities

- Parses MIPS assembly and 32-bit machine-code input
- Supports R-type, I-type, branch, jump, load/store, and NOP instructions
- Compares single-cycle and 5-stage pipelined processor performance
- Reports CPI, execution time, latency, throughput, and stall behavior
- Analyzes instruction dependencies and pipeline hazards
- Supports batch analysis of multiple MIPS workload files

This was a team project. The original repository is maintained by the project team, and the linked source preserves the complete collaborative development history.

[View the original project source code and documentation on GitHub](https://github.com/zoeyeballard/PipeCleaner).
