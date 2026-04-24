# OpenGL Gravity Simulation

OpenGL Gravity Simulation

A real-time gravity simulation built with modern OpenGL, implementing Newton’s Law of Universal Gravitation.

## Features
N-body gravity simulation
Real-time rendering using OpenGL
Basic physics integration (position, velocity, acceleration)
Expandable for more complex simulations (collisions, GPU compute, etc.)
## How it works

Each particle attracts every other particle using Newton’s law of gravitation:

F = G * (m1 * m2) / r²

For each frame:

Forces are calculated between all particles
Acceleration is derived from force
Velocity and position are updated over time

## Built with:
```
- OpenGL
- GLFW
- GLAD
```

## Requirements:
```
C++ compiler (MSVC / GCC / Clang)
CMake (recommended)
```
