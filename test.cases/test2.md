# Test Case 2: Manual Override and Emergency Stop

Purpose
Ensure that the manual switch can override automatic control, and emergency stop disables all outputs.

Preconditions
- System is in automatic mode (inputs functional).
- Manual switch is enabled.
- No light/dark dependency in this test.

Step 1 — Manual Light ON
Input States
- I1: OFF (door closed)
- I2: OFF (light)
- I3: ON (manual switch pressed)
- I4: ON (no emergency)

Expected Output
- Q1: ON (light manually activated)
- Q2: ON (system status active)

Step 2 — Emergency Stop
Input Change
- I4: OFF (emergency triggered)

Expected Output
- Q1: OFF
- Q2: OFF

Notes
- After emergency, system should stay OFF until reset.
- Manual and auto triggers should be locked out by emergency.
