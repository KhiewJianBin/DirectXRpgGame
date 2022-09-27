# DirectXRpgGame
  Course Assignment Project in Singapore Polytechnic.

  "apocalypse_dilivery"
  Simple 3D Shooter RPG Game made using DirectX9 No guided objectives.
  
  Created by:
  Programmer :Khiew Jian Bin
  Designer   :Song JunQuan

  <img src="https://user-images.githubusercontent.com/5699978/192591899-bb05f794-a554-4c93-979c-a337ab9f68ac.png" width="700">
  
# Features
  1. First person or third person mode
  2. A Shop to buy ***Health** and *Ammo*
  3. FreeCam Mode for screen Shots
  4. Procedural Level that loads from text [file] (https://github.com/KhiewJianBin/DirectXRpgGame/blob/main/RpgGame/media/maze.txt)
  5. Modifiable Game Settings [Stats](https://github.com/KhiewJianBin/DirectXRpgGame/blob/main/RpgGame/media/Stats.txt)
  
# Install
  No Installation Required. Just Git clone or direct download

## Usage
1. Run [My3DGame.exe](https://github.com/KhiewJianBin/DirectXBlockSimulation/blob/main/My3DGame.exe)

## Instructions

> Warning! Alt-Tab Not Supported Quit Game Before Doing Any other stuff

### Game Controls

```
Esc - Pause/Quit
F1 - First Persion View
F2 - Third Person View
F3 - Free Camera View
```

### Player Controls
```
WASD - Movement
Left Mouse - Shoot
E - Talk to NPC (Shop & Quest Giver)
```

### Free Cam Controls

```
WASD - Movement
Q/E - Rise/Fall 
Hold Shift - Faster Movement
F2 - Front View 
F3 - Perspective View
F4 - Free Look - Changes To Camera Mode
```

## Notes
- Very basic implementation of rpg game concept

## Dev Notes
- Uses Hightmap to generate Terrain 
- Locks Mouse to center of window
- For Wall Collision: Uses a cached "Old Positon" and Axis Clamping to reset Position when Collision
- All Uses Basic Radius distance for collsion detection
