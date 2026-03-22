# Minecraft C++ Clone

## Description
This project aims to build a voxel engine with OpenGL and GLFW from scratch, creating a clone of Minecraft using C++.

## Installation Instructions
1. Make sure you have the following dependencies installed:
   - CMake
   - OpenGL
   - GLFW
   - GLEW
   - GLM

2. Clone the repository:
   ```bash
   git clone https://github.com/GoBlockz/minecraft-cpp.git
   cd minecraft-cpp
   ```

3. Install the dependencies using your package manager. For example, on Ubuntu:
   ```bash
   sudo apt install cmake libglfw3-dev libglew-dev libglm-dev
   ```

## Build Instructions
1. Create a build directory:
   ```bash
   mkdir build
   cd build
   ```

2. Run CMake:
   ```bash
   cmake ..
   ```

3. Build the project:
   ```bash
   make
   ```

## Roadmap
The development of this project is planned in 11 phases:
1. Setting up the project structure
2. Basic rendering setup with OpenGL
3. Handling input using GLFW
4. Implementing basic voxel structure
5. Terrain generation
6. Player movement and camera control
7. Block interactions and inventory system
8. World saving and loading
9. Multiplayer support
10. Optimization and performance enhancements
11. Final touches and release
