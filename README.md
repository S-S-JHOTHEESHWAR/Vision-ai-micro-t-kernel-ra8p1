# Vision AI using Micro T-Kernel on RA8P1

> 🚧 **Work in Progress**
>
> This repository contains an embedded Vision AI project under active development for the **TRON Programming Contest 2026**. The goal is to build a real-time Vision AI system on the Renesas EK-RA8P1 platform using Micro T-Kernel 3.0.

---

## Overview

The project aims to develop a complete embedded Vision AI pipeline capable of:

- Capturing images from a camera
- Running neural network inference on the Arm Ethos-U55 NPU
- Displaying results on an LCD
- Managing large AI models using external SDRAM and OSPI Flash
- Integrating the complete pipeline with Micro T-Kernel 3.0

This repository is under continuous development and new features are added regularly.

---

## Current Progress

- Camera interface initialization
- LCD display pipeline
- SDRAM configuration
- OSPI Flash support
- Arm Ethos-U55 integration
- TensorFlow Lite Micro integration
- AI inference pipeline development
- Vision application framework

---

## Planned Features

- Real-time object detection
- OCR (Optical Character Recognition)
- Camera preprocessing pipeline
- Multi-threaded Micro T-Kernel application
- Performance optimization
- Complete Vision AI user interface

---

## Hardware Platform

- Renesas EK-RA8P1 Evaluation Kit
- RA8P1 Cortex-M85 MCU
- Arm Ethos-U55 NPU
- External SDRAM
- External OSPI Flash
- MIPI CSI Camera
- RGB LCD Display

---

## Software Stack

- C
- Renesas FSP 6.5.0
- e² studio
- Arm Clang Toolchain
- TensorFlow Lite Micro
- CMSIS-NN
- Arm Ethos-U Driver
- DAVE2D Graphics Engine
- Micro T-Kernel 3.0 *(integration in progress)*

---

## Configured Hardware Drivers

- GLCDC (Graphics LCD Controller)
- VIN (Video Input)
- MIPI CSI
- MIPI PHY
- OSPI Flash
- I2C Master
- DMAC
- DAVE2D
- UART
- Ethos-U Driver

---

## Repository Status

| Module | Status |
|---------|--------|
| Board Bring-up | ✅ Complete |
| Camera Driver | ✅ Complete |
| LCD Display | ✅ Complete |
| AI Runtime | ✅ Complete |
| Ethos-U55 Integration | ✅ Complete |
| Object Detection | ✅ Complete |
| OCR | 🚧 In Progress |
| Micro T-Kernel Integration | 🚧 In Progress |
| Documentation | 🚧 Ongoing |

---

## Project Structure

```
src/
├── ai/
├── camera/
├── display/
├── drivers/
├── ethosu/
├── middleware/
├── rtos/
├── docs/
└── README.md
```

---

## Disclaimer

This project is actively under development. APIs, source code, and project structure may change as development progresses.

---

## License

MIT License
