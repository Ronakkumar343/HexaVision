# HexaVision 🕷️
A 6-legged autonomous exploration robot built for **Hack Club Fallen**.

## About the Project
HexaVision is a hexapod robot designed to walk across rough surfaces using biomimetic insect gaits. Instead of wheels that get stuck on rocks or sand, it uses 6 articulated legs powered by metal-gear digital servos and an ESP32 microcontroller, with a camera on front for computer vision.

## How It Works
* **Brain:** ESP32-S3 microcontroller running inverse kinematics and gait calculations.
* **Legs:** 6 legs with 12 high-torque servos (2 per leg) moving in alternating tripod steps.
* **Power:** Isolated 2S LiPo battery with an 8A buck regulator so motors never reset the computer.
* **Vision:** ESP32-CAM module mounted on the chassis for live visual tracking.

## Repository Contents
* `bom.csv`: Full itemized bill of materials and Daraz procurement links.
* `cad/`: 3D printable parts modeled in FreeCAD.
* `firmware/`: Motor control and tripod gait code.
