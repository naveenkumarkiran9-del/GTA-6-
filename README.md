🏙️ CITY LIFE: OPEN WORLD – 3D Action Adventure

An original AAA-style 3D open-world action-adventure game built with Three.js and Web Audio API.

Explore the metropolis of San Nova on foot or behind the wheel of supercars, SUVs, and police interceptors with realistic vehicle physics, a dynamic circular radar minimap, day/night atmospheric weather cycles, a 5-star police wanted system, and a full 10-mission story campaign.

🎮 Key Gameplay Systems
1. 🌆 Massive 3D Explorable Metropolis
Downtown Financial District: Sky towers with illuminated antenna crowns, commercial plazas, and neon rooftops.
Ocean Coastline & Marina: Sandy beaches, blue ocean water, marina piers, and coastal palm trees.
Metropolitan Airport: Terminal building, air traffic control tower, and lighted aircraft runway.
Elevated Expressways & Bridges: Concrete pillars and multi-lane overpasses.
Civic & Emergency Sector: City Hospital, Police Headquarters with helipad, and underground tunnel parking.
Central City Park: Green lawns, trees, and central water fountain.
2. 🚶 Third-Person Player Character
Seamless transitions between on-foot locomotion and vehicle driving.
Procedural gait animations (walking, sprinting, jumping with velocity arc, and camera alignment).
Health bar and stamina bar with sprint depletion and recovery.
Seamless vehicle entry & exit at driver doors ([E] or [F]).
3. 🏎️ Realistic Vehicle Handling & Physics
Controllable Vehicle Classes:
Venom GT (Supercar): High acceleration, aerodynamic spoiler, 240+ KM/H top speed.
Titan 4x4 (SUV): Raised suspension, heavy mass, ramming bumper.
Apex Interceptor (Police Cruiser): Emergency flashing sirens and pursuit acceleration.
Driving Physics: Speed-sensitive steering, tire slip angle, handbrake drifting with tire screech audio, functioning headlights, reverse gear, and collision bounce.
Dual Camera Angles:
Third-Person Chase Cam (with speed-based FOV pull-back).
First-Person / Cockpit Hood Cam ([C] to toggle).
4. 📜 10 Original Story Missions
Mission 1: Welcome to San Nova – Orientation, explore the boulevard, and commandeer your first car.
Mission 2: First Drive – Hit 120+ KM/H along Ocean Boulevard to the coastal checkpoint.
Mission 3: Meet the Contact – Drive to the Marina Pier to rendezvous with informant Marcus.
Mission 4: City Exploration – Inspect the International Airport runway and flight terminal.
Mission 5: High-Priority Delivery – Rush cross-town to deliver blueprints to the Sky Tower plaza.
Mission 6: Highway Speed Trap – Max out velocity across the elevated expressway overpass.
Mission 7: The Heat is On – Evade a 2-star police lockdown and reach the underground tunnel safehouse.
Mission 8: Neon Underground – Illegal midnight sprint through the club district.
Mission 9: Tri-Sector Heist Drop – Multi-zone data collection culminating at the Central Park fountain.
Mission 10: King of San Nova – Grand finale victory loop to become a city legend!
5. 🚨 Police & Wanted Level System
1 to 5 Stars Wanted level indicator with pulsating stars.
Police pursuit with siren audio and patrol pursuit cruisers.
Evade line-of-sight to clear heat.
6. 🌦️ Dynamic Environment & Weather
Time & Weather Presets: Clear Noon, Golden Sunset, Cyber Night, Torrential Storm Rain.
Rain particle system (1,500 falling drops) with soundscape.
Automatic streetlights and vehicle headlights turning on at dusk.
7. 🔊 Procedural Web Audio Engine (Zero External Audio Files)
Multi-oscillator vehicle engine audio linked to RPM, gear shifting, and throttle.
Tire screech audio during handbrake drift.
Footsteps cadence audio.
Police siren wail and yelp synthesizer.
Rain noise generator and mission victory fanfare.
⌨️ Game Controls
Desktop Controls
Key	Action
W, A, S, D / Arrow Keys	Move / Accelerate & Steer
Shift	Sprint (On Foot)
Space	Jump (On Foot) / Handbrake Drift (In Car)
E or F	Enter / Exit Vehicle
C	Toggle Camera (3rd Person ↔ Cockpit Hood)
Mouse Drag	Orbit & Rotate Camera
Esc	Pause Menu
Mobile Controls
On-Screen D-Pad: Move / Drive forward, backward, left, right.
Action Buttons: SPRINT, JUMP / HANDBRAKE, CAR (Enter/Exit), CAM.
🚀 How to Launch & Play
Option 1: One-Click Launcher (Windows)

Double-click start.bat in this folder. It launches the local server on http://localhost:3001 and opens your default browser.

Option 2: Terminal Command

Run inside C:\Users\Naveen Kumar\.gemini\antigravity\scratch\city-life-game:

powershell
node server.js

Or with Antigravity Node:

powershell
& "$env:APPDATA\Antigravity\bin\agy-node.cmd" server.js

Then open http://localhost:3001
.

Option 3: Direct Browser Launch

Open public/index.html directly in Google Chrome or any modern WebGL browser.
