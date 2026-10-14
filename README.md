# Leziga Beage | Electrical Engineering Portfolio

A portfolio of electrical-engineering projects focused on embedded systems, FPGA and digital design, computer architecture, and hardware/software integration.

## Featured Projects

| Project | Engineering Highlights | Repository |
| --- | --- | --- |
| [Autonomous Navigation & Control Robot](projects/autonomous-navigation-control-robot.md) | TI TM4C123GXL robot using embedded C, TI-RTOS, IR sensing, PWM motor control, UART/Bluetooth communication, and real-time wall-following control. | [Source & documentation](https://github.com/LezBe/Autonomous-Navigation-Control-Robot) |
| [FPGA Binary Sequence Memory Game](projects/fpga-binary-sequence-memory-game.md) | Modular Verilog design for the DE0-CV with authentication, LFSR sequence generation, countdown timing, score memory, and FSM control. Module-level simulation verification and partial hardware bring-up; sequence-display integration remains unresolved. | [Source & documentation](https://github.com/LezBe/FPGA-Binary-Sequence-Memory-Game) |
| [PipeCleaner — MIPS Pipeline Performance Analyzer](projects/pipecleaner-mips-pipeline-performance-analyzer.md) | Collaborative Python project comparing single-cycle and five-stage pipelined MIPS performance using hazard-based stall estimates. My contributions focused on hazard detection, stalls, flushes, and forwarding logic. | [Original team repository](https://github.com/zoeyeballard/PipeCleaner) |

PipeCleaner is referenced here as a team project; its source and development history remain in the original repository.

## Portfolio Structure

This repository contains the existing TechFolio/Jekyll portfolio site:

- [`projects/`](projects/) — project summaries and links to source repositories.
- [`essays/`](essays/) — writing and reflections.
- [`resume.html`](resume.html) and [`_data/bio.json`](_data/bio.json) — resume page and profile data.
- `_layouts/`, `_includes/`, `css/`, and `img/` — site templates, styling, and assets.
- [`_config.yml`](_config.yml) — Jekyll configuration.

For framework setup and customization, see the [TechFolio documentation](https://techfolios.github.io/).
