# 🎮 MicroManagement - Sim Game

For my final year dissertation project, I created MicroManagement, a game that merges city-building and resource management mechanics. The aim is to keep the civilians on a planet alive for as long as possible by managing their tasks and planet resources!


<img width="1600" height="816" alt="image" src="https://github.com/user-attachments/assets/e53d66aa-7bc3-446e-9fe3-278b8bbeed7e" />

## Programs used
- Unity Game Engine for overall game creation and management
- Visual Studio for developing code in C#
- Piskel for pixel art

## Features
This project has been designed to be as modular as possible, with C# scripts separated by functionality for clarity and reusability in potential future projects. There are a few key features that form the foundation of MicroManagement:
- Building systems
    - Handles grid-based building placement and construction costs
- Resource management
  - Tracks resources and updates them depending on building placement or civilian tasks
- Civilian systems
  - Handles task assignment using finite state machine
  - Logic when a civilian dies
  - Manages sprite spawning and movement
- UI design
  - Panels for building selection, civilian information boxes, resource display and task capacities
  - Tilemap and sprite design
