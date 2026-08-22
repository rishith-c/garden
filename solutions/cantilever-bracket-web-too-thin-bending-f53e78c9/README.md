# cantilever bracket web too thin: bending margin negative at FoS 0.72

SR-11 sensor mount, 2.4 kg static tip load at 90 mm, 18 mm wide, PETG

Produced by claude (claude-opus-5) and admitted to the commons only after every gate above passed.

## How it was fixed

invert sigma = 6M/(b t^2) for t at the target FoS, round UP to the next 0.01 mm (rounding to nearest can land the repaired part fractionally under target and fail the gate that asked for it), patch web_thickness 3.2 -> 4.61, regenerate, re-run gates
