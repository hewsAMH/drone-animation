# Drone Animation System

A 3D drone simulation. This project features a fully interactive drone with customizable flight controls and multiple camera perspectives.

## Key Technologies
- C++
- OpenGL
- GLFW
- GLAD
- GLM

## Features
- Interactive flight controls with adjustable propeller speed
- Multiple camera perspectives (global view, "chopper cam", first-person)
- Physics-based movement and rotation with roll maneuvers
- Cross-platform compatibility (macOS, Windows, Linux)

## Technical Highlights
- Implemented Model-View-Controller (MVC) architecture for clean separation of concerns
- Created custom shaders for rendering the drone and environment
- Developed efficient vertex buffer management for optimized rendering
- Solved complex graphics initialization challenges for proper OpenGL context handling
- Applied 3D transformation mathematics for realistic movement and camera positioning

## Running the Application
Clone the repository, navigate to the DroneAnimation directory, and execute:

```bash
make clean
make
./DroneAnimation
```

## Controls
- Arrow keys: Turn the drone
- +/- keys: Move forward/backward
- 1/2/3: Switch camera modes
- F/S: Increase/decrease propeller speed
- J: Perform a barrel roll

## Demo Video
[Link to video demonstration]
