# Autonomous mobile robot

![Hero image](media/hero.jpg)

## Problem
Design and build a reliable autonomous mobile robot platform for hands-on work in mechatronics, controls, and embedded systems. The project was built to bridge theory and real-world implementation by integrating mechanical design, electronics, firmware, and higher-level software into one complete system.

## Key specs
- Differential-drive mobile base with onboard compute and sensing
- Modular mechanical architecture for rapid iteration and maintenance
- Embedded motor control and sensor interfacing via microcontroller firmware
- High-level autonomy stack in Python/ROS for navigation and behavior logic
- End-to-end workflow from CAD and fabrication through software validation

## My role
- Owned full system development from concept through integration and test
- Designed mechanical assemblies in CAD and prepared fabrication-ready outputs
- Built electronics stack and handled wiring, power distribution, and bring-up
- Developed firmware for low-level control, communications, and sensor handling
- Implemented autonomy software and test workflows for iterative improvements

## Design decisions
- **Modular subsystems:** Separated chassis, electronics, firmware, and autonomy layers to reduce coupling and speed debugging
- **Hybrid control architecture:** Used microcontroller-level real-time control with higher-level planning in software for better reliability
- **Versioned engineering artifacts:** Kept CAD, electronics, firmware, and software structured for reproducibility and clean handoffs
- **Data-informed tuning:** Logged test behavior and adjusted control/navigation parameters based on measured performance

## Results
- Produced a functioning autonomous robot prototype capable of repeatable test runs
- Established a reusable project structure for future robotics builds
- Improved system reliability through iterative integration, test, and refinement cycles
- Demonstrated practical cross-domain engineering from mechanical through software

## What went wrong and how I fixed it
- **Integration instability:** Early subsystem integration exposed intermittent failures; I introduced staged bring-up and interface checks between layers
- **Control tuning challenges:** Initial motion behavior showed drift/oscillation; I improved controller gains and added repeatable calibration steps
- **Power/noise issues during bring-up:** Mixed-load behavior caused inconsistent sensor readings; I refined grounding, routing, and power distribution practices

## What I’d change
- Add a more formal verification matrix with pass/fail criteria for each subsystem
- Increase simulation-first testing before hardware iteration to reduce cycle time
- Expand telemetry tooling and automated test scripts for regression checks
- Package the autonomy stack for easier deployment and reproducibility

## Layout
Only create the folders the project uses:
`cad/` (SolidWorks), `cad/step/` (STEP exports), `drawings/` (PDFs), `electronics/` (KiCad, schematic PDF, Gerbers),
`firmware/` (Arduino), `software/` (Python, ROS), `docs/` (data, plots, reports), `media/` (photos, videos).
