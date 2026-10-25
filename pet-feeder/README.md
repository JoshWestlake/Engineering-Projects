# Pet feeder

![Hero image](media/hero.jpg)

## Problem
Design and build an automated pet feeder that dispenses food reliably on demand or on a schedule. The aim was a practical, everyday mechatronic product covering mechanism design, control, and user-facing behavior.

## Key specs
- Motor-driven dispensing mechanism with a food hopper
- Microcontroller control for scheduled or triggered portions
- Designed around portion consistency and jam avoidance
- CAD-designed enclosure and printable/fabricated parts

## My role
- Designed the dispensing mechanism and enclosure in CAD
- Selected the motor and built the electronics
- Wrote firmware for dispensing and scheduling logic
- Tested the feeder with real food

## Design decisions
- **Controlled dispensing:** Metered portions mechanically rather than relying on timing alone
- **Jam tolerance:** Shaped the hopper and dispenser to reduce bridging and blockage
- **Simple user operation:** Kept interaction minimal and predictable

## Results
- Working feeder that dispenses portions automatically
- Complete design files and firmware in a structured project
- Practical experience with product-style mechatronic design

## What went wrong and how I fixed it
- **Food jamming:** Kibble bridged or wedged in the mechanism; I changed hopper geometry and dispenser clearances
- **Inconsistent portions:** Output varied with fill level; I adjusted the metering design and control
- **Motor stalls:** Jams could overload the drive; I improved clearances and added stall handling

## What I’d change
- Add a load cell to verify dispensed portion weight
- Add connectivity or an app for remote scheduling
- Make the hopper easier to fill and clean
- Test with a wider variety of food types

## Layout
Only create the folders the project uses:
`cad/` (SolidWorks), `cad/step/` (STEP exports), `drawings/` (PDFs), `electronics/` (KiCad, schematic PDF, Gerbers),
`firmware/` (Arduino), `software/` (Python, ROS), `docs/` (data, plots, reports), `media/` (photos, videos).
