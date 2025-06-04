# Test Case 1: Automatic Light ON in Darkness

Purpose
Verify that the garage light automatically turns ON when the door opens in dark conditions.

Preconditions
- PLC is powered ON and program is running.
- All sensors and output devices are connected correctly.
- Light level is DARK (light sensor = active).
- Light is currently OFF.

Input States
- I1 (Garage Door Sensor): ON (door is open)
- I2 (Light Sensor): ON (darkness detected)
- I3 (Manual Switch): OFF
- I4 (Emergency Switch): ON (no emergency)

Expected Output
- Q1 (Garage Light): ON
- Q2 (Status LED): ON

Additional Behavior
- Timer starts countdown (e.g., 5 minutes).
- If no manual interaction, light will turn OFF after timeout.

Notes
- This test validates automatic trigger logic.
- Useful to confirm input priority and auto-mode functionality.
