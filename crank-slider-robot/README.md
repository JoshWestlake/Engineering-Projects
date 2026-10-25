# Crank-slider robot

![Hero image](media/hero.jpg)

## Problem
Build a robot driven by a crank-slider mechanism to convert continuous rotary motion into controlled linear motion. The project was used to apply kinematic analysis and mechanism design to a physical, actuated system rather than leaving it as a textbook exercise.

## Key specs
- Crank-slider linkage converting motor rotation into linear slider travel
- Stroke and motion profile set by crank radius and connecting-rod length
- Motor-driven actuation with microcontroller control
- CAD-designed linkage with fabricated and/or printed parts

## My role
- Designed the linkage and mechanical assemblies in CAD
- Analyzed slider position, velocity, and transmission angles to size links
- Selected actuation and wired the electronics
- Wrote control firmware and tested the assembled mechanism

## Design decisions
- **Kinematics first:** Sized crank and rod lengths from the required stroke before detailed CAD, keeping transmission angles away from singular positions
- **Simple, serviceable joints:** Used straightforward pin joints and fasteners so links could be swapped and re-tuned
- **Rigid slider guidance:** Constrained the slider on a linear guide to limit side loading on the linkage

## Results
- Working crank-slider robot demonstrating the intended linear motion from rotary input
- Hands-on validation of the kinematic model against the physical mechanism
- Reusable mechanism design approach for later projects

## What went wrong and how I fixed it
- **Joint play and backlash:** Loose pin fits caused slop in slider position; I tightened tolerances and fit/fastener choices
- **Binding near end of stroke:** Misalignment and friction increased load; I improved guide alignment and link geometry
- **Motor loading:** Peak torque occurs at unfavorable crank angles; I reviewed motor sizing and drive settings against the load

## What I’d change
- Add position feedback for closed-loop control of the slider
- Measure and document performance rather than relying on observation
- Use stiffer materials or bearings at the joints to reduce wear and play
- Run a dynamic analysis to size the motor with more margin

## Layout
Only create the folders the project uses:
`cad/` (SolidWorks), `cad/step/` (STEP exports), `drawings/` (PDFs), `electronics/` (KiCad, schematic PDF, Gerbers),
`firmware/` (Arduino), `software/` (Python, ROS), `docs/` (data, plots, reports), `media/` (photos, videos).
