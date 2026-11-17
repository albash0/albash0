# Aerospace engineering + creative technology

I'm a first-year **Aerospace Engineering Sciences (ASEN) and Creative Technology & Design (CTD) student at the University of Colorado Boulder**. I build projects that connect embedded software, electronics, and physical design, with an interest in making hardware useful and understandable to the person holding it.

## Featured projects

| Project | What I worked on | Explore |
| --- | --- | --- |
| **OpenCamera — in progress** | Mostly 3D-printed 35 mm SLR prototype combining mechanical/optical design, ESP32-C3 control, a motor-driven shutter, a servo mirror, and IR timing feedback. | [Prototype, CAD and build documentation](https://github.com/albash0/OpenCamera) |
| **MiniConsole** | ESP32-S3 handheld with OLED and color TFT versions, custom carrier PCBs, a printable enclosure, game firmware, and wireless play between two consoles. | [Project and engineering notes](https://github.com/albash0/MiniConsole) |
| **Waypoint Compass** | Offline GPS navigation device with a round display, magnetometer calibration, tilt compensation, and modular and compact PCB designs. | [Project and engineering notes](https://github.com/albash0/WaypointCompass) |

MiniConsole and Waypoint Compass include development timelines, source, hardware files, build instructions, and validation notes. OpenCamera documents its V71 prototype, design history, controller firmware, and remaining development work.

## Current focus: OpenCamera

| Physical V71 prototype | Engineering focus |
| --- | --- |
| <img src="https://raw.githubusercontent.com/albash0/OpenCamera/main/docs/images/opencamera-prototype.png" alt="Physical OpenCamera V71 prototype with exposed electronics and batteries" width="180"> | Bringing a film path, lens/mirror geometry, printed mechanisms, and embedded control into one device. A servo moves the mirror, a DC motor drives the rack-and-pinion shutter, and an IR sensor supplies timing data for an exposure estimate. Film advance is currently manual. Light sealing, focus, shutter calibration/repeatability, and electronics integration remain development work. |

*Existing prototype photograph from OpenCamera's public project documentation. [Explore the current design and limitations →](https://github.com/albash0/OpenCamera)*

## Tools I use in these projects

- **Embedded systems:** C/C++, ESP32, Arduino, SPI, I²C, UART, and ESP-NOW.
- **Hardware and physical design:** KiCad PCB design, Fusion CAD, protoboard electronics, printed mechanisms, and enclosures.
- **Development and validation:** Python tooling, Git/GitHub, automated C++ tests, and hardware bring-up.

## What I'm working on

I'm developing my ability to take a device from an idea through firmware, electronics, mechanical fit, and testing. I'm continuing OpenCamera's prototype development while making MiniConsole and Waypoint Compass easier to reproduce and documenting the decisions behind them.

The project pages distinguish my integration and design work from upstream code and libraries. In particular, MiniConsole's Doom support adapts the existing DIABLITO engine; the original authors and licenses are credited in the repository.
