# python-raycasting-engine
Creating a ray casting engine similar to classic Doom and Wolfenstein in Python.

## Classes

### Game
Contains the main game loop and the main class that initiates the game.

### Player
The main player class.
#### Properties
`x` Player X position<br />
`y` Player y position<br />
`direction` The direction the player is facing<br />
`pace` Movement velocity<br />

### State
Handles the game state.<br />
- Main menu
- Game

### PlayerControl
Handles player keyboard and mouse input

### Map
The Map class

### Camera
Handles camera placement

