# Cycloidal gearbox

![Hero image](media/hero.jpg)

## Problem
Design and build a compact, high-reduction cycloidal gearbox. Cycloidal drives offer high torque density and low backlash, and the project explores how well that can be achieved in a design that is practical to manufacture and assemble.

## Key specs
- Cycloidal reduction stage with eccentric input, cycloidal disc, and pin/roller ring
- High single-stage reduction ratio in a compact envelope
- Designed for low backlash and shock-load tolerance
- Parametric SolidWorks model with STEP exports and drawings

## My role
- Designed the gearbox in CAD, including the cycloidal disc profile and housing
- Prepared drawings and manufacturing outputs
- Selected bearings, fasteners, and fits
- Assembled and tested the gearbox

## Design decisions
- **Parametric design:** Driven by pin count, eccentricity, and disc profile so ratio and geometry could be adjusted together
- **Eccentric balance:** Considered counterweighting or dual discs to limit vibration
- **Manufacturability:** Chose tolerances and materials suited to the available fabrication methods

## Results
- Produced a complete gearbox design with CAD, STEP exports, and drawings
- Demonstrated the high-reduction, compact-envelope concept in hardware
- Built practical knowledge of cycloidal profile generation and fits

## What went wrong and how I fixed it
- **Profile and tolerance sensitivity:** Small errors in the disc profile caused binding or noise; I adjusted clearances and refined the profile
- **Assembly difficulty:** Aligning discs, pins, and bearings was fiddly; I revised the design for easier assembly
- **Friction and wear:** Sliding contact increased losses; I reviewed surface finish and lubrication

## What I’d change
- Measure efficiency, backlash, and torque capacity with a proper test rig
- Improve manufacturing accuracy of the disc and pin ring
- Consider a dual-disc layout for better balance
- Add an FEA review of the highest-loaded components

## Layout
Only create the folders the project uses:
`cad/` (SolidWorks), `cad/step/` (STEP exports), `drawings/` (PDFs), `electronics/` (KiCad, schematic PDF, Gerbers),
`firmware/` (Arduino), `software/` (Python, ROS), `docs/` (data, plots, reports), `media/` (photos, videos).
