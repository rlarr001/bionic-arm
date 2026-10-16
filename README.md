# Bionic Arm

A bionic arm project built by Roi and Alanis. It combines an Arduino-based control system, Python software, and custom-designed mechanical parts (CAD).

## Overview

_TODO: 2-3 sentences on what the arm does. Example: "A low-cost bionic arm that reads muscle (EMG) signals and moves a 5-finger hand."_

## Repository Structure

```
bionic-arm/
├── firmware/    # Arduino code (.ino) that runs on the microcontroller
├── software/    # Python code (signal processing, testing, control scripts)
├── cad/         # CAD models (.step, .stl) and design notes
├── docs/        # Wiring diagrams, photos, notes
└── README.md
```

## Hardware

_TODO: fill in what you actually use._

| Part | Purpose |
|------|---------|
| Arduino (model?) | Main controller |
| Servos / motors | Finger and wrist movement |
| Sensors (EMG? flex? force?) | Input signals |
| Power supply / battery | Powers servos and board |
| 3D-printed parts | Hand, fingers, forearm housing |

## Getting Started

### Firmware (Arduino)
1. Install the [Arduino IDE](https://www.arduino.cc/en/software).
2. Open the `.ino` file in `firmware/`.
3. Select your board and port, then upload.

### Software (Python)
```bash
cd software
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

### CAD
Models are in `cad/`. Export `.stl` files for 3D printing. Keep the original source files (e.g. Fusion 360, Onshape, SolidWorks) alongside them when possible.

## Team

- **Roi**
- **Alanis**

## Status

_TODO: e.g. "Prototype in progress", "Finger actuation working", etc._

## License

_TODO: add a license (MIT is a common choice for student projects)._
