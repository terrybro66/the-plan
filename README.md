
# Sound Landscape

Sound Landscape** is a 3D environment where players navigate a maze using both visual and auditory cues. Dynamic, real-time music adapts to the player's actions, guiding them through the maze

## Key Features

- **Dynamic Music**: Powered by **Magenta.js**, the game generates real-time music that changes based on gameplay.  
  - **Pitch**: Indicates proximity to goals.
  - **Rhythm**: Reflects player movement and nearby obstacles.
  - **Timbre**: Changes with different maze sections.

- **3D Maze**: Created using **Three.js**.

- **Audio Cues**: Music provides essential hints, guiding players through the maze. 


## Implementation Plan

1. **Environment Setup**: Build the 3D maze using **Three.js** and manage state with **React**.
2. **Music Integration**: Use **Magenta.js** to generate music that adapts to player actions:
   - **Pitch** increases as the player nears the exit.
   - **Rhythm** intensifies with speed and proximity to dangers.
   - **Timbre** varies by maze section and environment.
3. **Gameplay Mechanics**:
   - **Movement**: Navigate using WASD/arrow keys.
   - **Audio Cues**: Guide players through the maze with harmonized melodies and alert tones.


