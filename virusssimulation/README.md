# Virus Spread Simulation

A Python-based simulation that visualizes how viruses spread through a population, with various configurable parameters and interactive features.

## Features

- **Multiple Map Sizes**
  - Small (1920x1080)
  - Medium (3840x2160)
  - Large (5760x3240)

- **Interactive Controls**
  - Camera zoom and pan
  - Pause/Resume simulation
  - Change map size during simulation
  - Adjustable simulation parameters

- **Configurable Parameters**
  - Population size (up to 1000)
  - Initial infection percentage
  - Infection radius
  - Infection chance
  - Death chance
  - Recovery chance
  - Recovery time
  - Movement speed

- **Visual Elements**
  - Buildings and streets
  - Hospital and cemetery
  - Color-coded population status
  - Real-time statistics

## Controls

- **Mouse Controls**
  - Left-click and drag: Pan the map
  - Scroll wheel: Zoom in/out

- **Keyboard Controls**
  - Space: Pause/Resume simulation
  - M: Change map size
  - ESC: Exit simulation

## Installation and Running

1. Ensure you have Python installed on your system
2. Install required dependencies:
   ```
   pip install pygame
   ```
3. Run the simulation:
   - Double-click `start.bat` to launch the simulation
   - Or run `python virus_simulator.py` from the command line

## Credits and License

This project is created and maintained by Brolge.

You are free to use and modify this software for your own purposes, but please:
- Do not claim credit for creating this software
- Acknowledge the original creator (Brolge) if you share or modify the code
- Respect the open-source nature of the project

## Recent Updates

- Added multiple map size options (Small, Medium, Large)
- Implemented camera zoom and pan functionality
- Increased maximum population size to 1000
- Added map size selection screen at startup
- Improved UI layout and statistics display
- Added keyboard shortcuts for common actions
- Fixed various bugs and improved performance

## Technical Details

- Built with Python and Pygame
- Uses object-oriented programming principles
- Implements efficient collision detection
- Features smooth camera controls
- Real-time simulation updates 
