marlin_prusai3_diegudio
========================

Marlin firmware adapted for a Prusa i3 3D printer with the following hardware configuration:

- Arduino 2560 board
- RAMPS 1.4 with StepStick A4988 Stepper Driver Module
- Geared extruder
- NEMA 17 stepper motors from Wantai Motors (P/N 42BYGHW811)
- Opto-endstops at min location (0,0,0). No max endstops (deactivated in Marlin)
- T2.5 16 teeth pulleys for X and Y axis (80.00 steps/unit)
- M5 threaded bolts for Z axis (4000 steps/mm)

The steps have been calculated using Prusa's v3 calculator (http://calculator.josefprusa.cz/)
considering that the A4988 steppers are running at 1/16 uSteps
