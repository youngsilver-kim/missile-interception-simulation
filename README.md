# Missile Interception Simulation

An interactive 3D missile interception simulation built with Three.js.  
This project visualizes the trajectory of an incoming enemy missile and the launch of an interceptor missile from a defense base, showing their movement and interception point in a 3D environment.

## Overview

This simulation demonstrates a simplified missile defense scenario:

- An enemy missile follows a ballistic-style trajectory
- A defense base launches an interceptor missile
- The interceptor travels toward the computed interception point
- The entire process is visualized in real time in a 3D scene

The project was implemented to practice trajectory modeling, 3D visualization, animation control, and interactive web-based simulation design.

## Features

- 3D scene rendered with Three.js
- Real-time animation of enemy and interceptor missiles
- Automatically computed interception point
- Interactive camera controls with OrbitControls
- Launch and reset button controls
- Grid and axis helpers for spatial understanding
- Visual impact effect at the interception point

## Project Structure

```bash
missile-interception-simulation/
├─ index.html
├─ style.css
├─ script.js
├─ README.md
└─ assets/
   ├─ preview.png
   └─ demo.gif
