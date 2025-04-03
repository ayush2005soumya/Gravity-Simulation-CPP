# Gravity Simulation

A real-time gravity simulation using OpenGL, GLFW, and GLEW, visualizing planetary motion with physics-based interactions in a 3D environment. 🚀🌍

## Features

- Real-time 3D simulation of gravitational interactions
- OpenGL rendering with GLFW and GLEW
- Interactive camera controls
- Smooth physics-based motion

## Installation

### Prerequisites

Make sure you have the following dependencies installed:

- OpenGL
- GLFW
- GLEW
- GLM (for math operations)

### Windows Setup

1. Install [GLEW](http://glew.sourceforge.net/) and [GLFW](https://www.glfw.org/).
2. Copy `glew32.dll` and `glfw3.dll` to your project directory.
3. Compile using MinGW:
   ```bash
   g++ grav_sim_1.cpp -o Gravity_Simulation -I<path_to_glew>/include -I<path_to_glfw>/include -L<path_to_glew>/lib -L<path_to_glfw>/lib -lglew32 -lglfw3 -lopengl32
   ```

### Linux Setup

1. Install dependencies:
   ```bash
   sudo apt update
   sudo apt install libglew-dev libglfw3-dev libglm-dev
   ```
2. Compile using g++:
   ```bash
   g++ grav_sim_1.cpp -o Gravity_Simulation -lGLEW -lglfw -lGL -lm
   ```

## Usage

Run the executable:

```bash
./Gravity_Simulation
```

### Controls

- **ESC** → Toggle mouse lock
- **W/A/S/D** → Move camera
- **Mouse** → Look around

## Contributing

Feel free to fork and submit pull requests! 🚀

## License

This project is licensed under the MIT License.


