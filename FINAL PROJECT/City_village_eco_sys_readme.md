# OpenGL 2D Animated Scene

This project is a 2D animated graphical scene built using **OpenGL** and **GLUT** in C++. It showcases a vibrant environment with dynamic elements including a **waterfall**, **waves**, **windmills**, **buildings**, **cars**, and **day/night transitions**.

## Features

- 🌞 **Day and Night Mode**: Switch between day and night scenes, including changes in sky, lighting, and object colors.
- 💧 **Waterfall Animation**: A multi-stage animated waterfall with dynamic water flow.
- 🌊 **Waves Movement**: Layered wave effects simulating flowing water.
- 🚗 **Moving Cars**: Cars animated along roads with varying speeds and directions.
- 🌄 **Mountain Range**: Stylized background mountains to set the scene.
- 🌆 **Buildings and Towers**: Static and animated buildings with windows that react to day/night.
- 🌳 **Trees and Environment**: Decorative trees, houses, and landscape features.
- 🌬️ **Rotating Windmills**: Functional windmills with continuous blade rotation.
- 🌙 **Animated Sun & Moon**: Sun and moon move to simulate time progression.

## Technologies Used

- **C++**
- **OpenGL (GL, GLU, GLUT)**
- **Windows.h** (platform-specific headers for Windows)

## How to Compile

Ensure you have OpenGL and GLUT installed. On Windows, use an IDE like Code::Blocks or Visual Studio with OpenGL/GLUT libraries configured.

Example command using `g++`:

```bash
g++ main.cpp -o animated_scene -lglu32 -lopengl32 -lfreeglut
```

> Adjust libraries as needed for your OS and compiler.

## Running the Program

Run the compiled executable. The scene starts with a default view and runs continuously with animated elements.

```bash
./animated_scene
```

## Controls

Depending on how the rest of the code is implemented (e.g., keyboard or mouse input), day/night mode or other interactions might be toggleable with keys.


## License

This project is for educational and demonstration purposes. Feel free to modify and use it for your own learning.
