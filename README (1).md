# AC–AC Voltage Controller

## Overview

This project contains a MATLAB/Simulink model named `AC_AC_voltage_controller.slx` for an AC–AC voltage controller. The model file is intended to be opened and explored in MATLAB Simulink to inspect its circuit arrangement, control strategy, and simulated behavior.

An AC–AC voltage controller regulates the RMS voltage delivered to an AC load by controlling the portion of each AC supply cycle applied to the load. The exact topology, component values, firing/control method, and simulation results should be confirmed from the blocks and parameters inside the supplied Simulink model.

## Project File

- `AC_AC_voltage_controller.slx` — MATLAB/Simulink model.

## How to Open the Model

1. Install and open MATLAB with Simulink available.
2. Download or clone this repository.
3. Open MATLAB and navigate to the folder containing `AC_AC_voltage_controller.slx`.
4. Open the model by double-clicking the file, or run:

   ```matlab
   open_system('AC_AC_voltage_controller.slx')
   ```

5. Review the model blocks and parameters before running the simulation.
6. Click **Run** in Simulink and inspect the connected scopes or logged signals, if present.

## What to Review

- AC source settings and frequency.
- Controller topology and switching-device arrangement.
- Firing/control signals and their timing.
- Load parameters.
- Output voltage and current waveforms.
- RMS output voltage and any measured power-quality quantities.

## Requirements

- MATLAB
- Simulink
- Any additional MATLAB/Simulink toolboxes required by the model, if applicable.

The exact MATLAB release and toolbox requirements have not been specified; confirm them if the model reports missing blocks or compatibility issues.

## Notes

- This README describes the supplied model file at a high level. Specific topology, component ratings, control method, and numerical results are not stated here because they have not been verified from the model internals.
- Do not connect a simulated design to physical mains hardware without appropriate engineering review, isolation, and safety procedures.

## License

No license has been specified. Add a license if you intend to permit reuse or redistribution.
