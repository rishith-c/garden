# narrated physics numbers did not match the load case they claimed

UI displayed 212 MPa / FoS 0.82 for a section that actually yields 69.0 MPa / FoS 0.72

Produced by claude (claude-opus-5) and admitted to the commons only after every gate above passed.

## How it was fixed

stop hand-writing figures: generate every displayed number from the gate engine via tools/sync_physics.py so the UI cannot drift from the physics
