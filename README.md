PLC Garage Lighting System

🚗💡 This project implements an automatic garage lighting system using Siemens LOGO! 8 PLC. It turns on the light when the door opens in the dark and includes manual override and emergency stop features.

Features
- Auto turn-on light when garage door opens & it's dark
- Manual light switch
- Emergency stop
- 5-minute delay off timer
- Status LED indicator

Hardware
- Siemens LOGO! 8
- Garage door sensor (digital)
- Light sensor (digital)
- Manual switch (NO)
- Emergency stop switch (NC)
- Relay-connected light and LED

Logic Overview
Implemented using:
- Ladder diagram (LAD)
- Function block diagram (FBD)
- XML logic for LOGO!Soft Comfort

See diagrams in `/docs/`.

Simulation & Testing
Test cases for 4 scenarios:
- Auto on
- Manual on
- Daylight behavior
- Emergency shutdown

Installation
Wiring and programming instructions in [`/docs/installation.md`](docs/installation.md)

License
MIT License (or your preferred license)
