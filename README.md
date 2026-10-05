ROBOGEN – Smart Autonomous Warehouse Robot
Pick – Navigate – Avoid – Transport – Place
SIH 2026 · Problem Statement SIH26112 · Hardware · Theme: Autodesk
ROBOGEN is a modular autonomous mobile robot (AMR) for warehouse automation. It moves goods without continuous human control, using a mobile base, sensor-based navigation, a robotic arm and a warehouse-control dashboard.
This repository contains the virtual simulator, a single-page website (index.html) that models how the robot works.
Simulator features
A* route planning, with automatic re-planning when an obstacle blocks the route
Drag-and-drop obstacles (move, add, erase, randomize, clear), editable while the robot drives
Click any free cell and the robot drives there by itself
Warehouse orders: pickup (A1–A3), destination (B1–B4) and payload, handled one after another
Arm sequence animation: home, move, grip, lift, place
Robot dashboard: status, battery, task, location, destination, connection, workflow pipeline and telemetry
LiDAR ray view with nearest-obstacle distance
Pause, Emergency stop, speed control and an event log
Battery drain, with automatic return to the dock to charge when low
