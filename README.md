
# Sonic Maze Explorer

**Genre**: 3D Puzzle Adventure  
**Platforms**: Web (Desktop & Mobile)  
**Technologies**: React, Three.js, Magenta.js, Web Audio API

## Overview

**Sonic Maze Explorer** is a 3D puzzle game where players navigate a maze using both visual and auditory cues. Dynamic, real-time music adapts to the player's actions, guiding them through the maze while avoiding traps and solving puzzles. The game merges immersive 3D environments with procedurally generated music, creating a unique gameplay experience that intertwines sight and sound.

## Key Features

- **Dynamic Music**: Powered by **Magenta.js**, the game generates real-time music that changes based on gameplay.  
  - **Pitch**: Indicates proximity to goals.
  - **Rhythm**: Reflects player movement and nearby obstacles.
  - **Timbre**: Changes with different maze sections.

- **3D Maze**: Created using **Three.js**, each maze is procedurally generated, increasing in complexity with each level.

- **Audio Cues**: Music provides essential hints, guiding players through the maze. High pitches signal correct paths, while dissonant tones warn of dead-ends.


## Implementation Plan

1. **Environment Setup**: Build the 3D maze using **Three.js** and manage state with **React**.
2. **Music Integration**: Use **Magenta.js** to generate music that adapts to player actions:
   - **Pitch** increases as the player nears the exit.
   - **Rhythm** intensifies with speed and proximity to dangers.
   - **Timbre** varies by maze section.
3. **Gameplay Mechanics**:
   - **Movement**: Navigate using WASD/arrow keys.
   - **Audio Cues**: Guide players through the maze with harmonized melodies and alert tones.


