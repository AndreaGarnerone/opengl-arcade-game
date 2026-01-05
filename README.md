# OpenGL Arcade Game

This repository contains a **3D arcade-style game** developed in **C++ using OpenGL**.

The project was built as a personal game development experiment, focusing on real-time rendering, basic game mechanics, asset integration, and interactive systems rather than polished production-level features.

---

## Overview

The game is implemented using modern OpenGL and includes:

- Real-time 3D rendering
- Custom 3D models created in **Blender**
- Sound effects and audio feedback
- Basic game design mechanics (lives, difficulty, power-ups)
- Collision detection
- Multiple game states and menus

The goal of the project was to explore the full pipeline of a small OpenGL game, from assets to gameplay logic.

---

## Main Features

### Graphics
- Modern OpenGL rendering pipeline
- Shader-based rendering
- Model loading via **Assimp**
- Texture loading with **stb_image**
- Camera system with mouse and keyboard controls
- Text rendering using **FreeType**

### Game Logic
- Multiple game states (main menu, gameplay, pause, game over, guide)
- Difficulty levels (easy, medium, hard)
- Power-ups with timed effects
- Lives system with visual indicators
- Basic physics and collision detection using AABB

### Audio
- Sound effects and audio playback using **irrKlang**
- Audio feedback for gameplay events

---

## Assets

- 3D models were created manually using **Blender**
- Textures and materials are loaded at runtime
- Audio files are integrated directly into the gameplay loop

---

## Technologies Used

- **C++**
- **OpenGL**
- GLFW
- GLAD
- GLM
- Assimp
- FreeType
- irrKlang
- Blender (for 3D assets)

---

## Project Scope

This is a **personal and educational project**, developed to practice:

- Computer graphics programming
- Game loop architecture
- Asset loading and management
- Basic game design principles
- Integration of graphics, audio, and input handling

The project is not intended to be a full commercial game, but a complete and functional prototype.

---

## Build & Run

The project requires:

- A C++ compiler with C++17 support
- OpenGL-compatible GPU
- GLFW, GLAD, GLM, Assimp, FreeType, irrKlang

Build instructions may vary depending on the platform and setup.

---

## License

This project is intended for educational and personal use.
