# 4-DOF robotic arm

![Hero image](media/hero.jpg)

## Problem
Design and build a four-degree-of-freedom robotic arm to study manipulator kinematics, actuation, and control on real hardware. It connects forward and inverse kinematics theory to a physical system that can be commanded to reach target positions.

## Key specs
- 4 degrees of freedom with a gripper or end-effector
- Servo or motor actuation per joint with microcontroller control
- Forward and inverse kinematics for end-effector positioning
- CAD-designed links and joints, with firmware and software control

## My role
- Designed the arm links, joints, and mounting in CAD
- Derived the kinematic model and implemented it in software
- Built the electronics and wrote joint control firmware
- Tested and tuned arm motion

## Design decisions
- **Kinematic model drives layout:** Chose link lengths and joint ranges from the target workspace
- **Layered control:** Used low-level joint control in firmware with kinematics computed in software
- **Rigid, lightweight links:** Balanced stiffness against load on the shoulder joints

## Results
- Functional arm that moves to commanded positions using the kinematic model
- Hands-on validation of kinematics, actuation, and control concepts
- Reusable control and structure for future manipulator work

## What went wrong and how I fixed it
- **Shoulder joint loading:** Gravity loading strained the actuators; I reduced link mass and reviewed actuator selection
- **Joint jitter and sag:** Compliance and backlash hurt accuracy; I stiffened the structure and tuned control
- **Kinematic mismatches:** Model and hardware disagreed; I calibrated joint offsets and limits

## What I’d change
- Add joint feedback for closed-loop position control
- Add trajectory planning with smooth velocity profiles
- Use higher-stiffness drives or gearing at the shoulder
- Quantify repeatability and payload

## Layout
Only create the folders the project uses:
`cad/` (SolidWorks), `cad/step/` (STEP exports), `drawings/` (PDFs), `electronics/` (KiCad, schematic PDF, Gerbers),
`firmware/` (Arduino), `software/` (Python, ROS), `docs/` (data, plots, reports), `media/` (photos, videos).
