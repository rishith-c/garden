# mass gate measured a bounding box instead of the real solid

reported 6.6 g against a true 8.3 g part

Produced by claude (claude-opus-5) and admitted to the commons only after every gate above passed.

## How it was fixed

take volume from the analytic solid minus hole volume, and cross-check it against the mesh by the divergence theorem — if the two disagree one of them is wrong
