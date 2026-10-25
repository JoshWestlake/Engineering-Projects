# Lifebot

![Hero image](media/hero.jpg)

## Problem
Build Lifebot, a robotic system integrating mechanical design, electronics, and software. It was developed as a hands-on way to take a robotics concept from idea to a working prototype.

## Key specs
- Robotic platform with custom mechanical structure
- Microcontroller-based control and sensor/actuator interfacing
- Powered by an onboard battery with dedicated power distribution
- Structured CAD, electronics, and firmware workflow

## My role
- Developed the concept and defined system requirements
- Designed mechanical parts in CAD
- Built and wired the electronics
- Wrote firmware and tested the integrated system

## Design decisions
- **Modular subsystems:** Kept mechanical, electrical, and firmware layers separable for easier debugging
- **Iterative prototyping:** Built and tested in stages instead of integrating everything at once
- **Accessible components:** Used readily available parts to speed iteration

## Results
- Functioning prototype integrating mechanical, electrical, and software subsystems
- Documented design files in a reproducible project structure
- Experience taking a robotics project through full integration

## What went wrong and how I fixed it
- **Integration issues:** Subsystems that worked alone failed together; I adopted staged bring-up with interface checks
- **Power and wiring problems:** Noise and voltage drops caused unreliable behavior; I improved wiring and power distribution
- **Mechanical fit:** Parts needed revision after assembly; I updated CAD and reprinted or refabricated

## What I’d change
- Define measurable requirements and test criteria up front
- Add more thorough documentation and wiring diagrams
- Add telemetry and logging for easier debugging
- Plan for serviceability earlier in the mechanical design

## Layout
Only create the folders the project uses:
`cad/` (SolidWorks), `cad/step/` (STEP exports), `drawings/` (PDFs), `electronics/` (KiCad, schematic PDF, Gerbers),
`firmware/` (Arduino), `software/` (Python, ROS), `docs/` (data, plots, reports), `media/` (photos, videos).
