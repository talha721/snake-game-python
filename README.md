# Snake Game

A classic Snake game implementation in Python using the turtle graphics library.

## Features

- Player-controlled snake that grows when eating food
- Real-time score tracking
- Collision detection with walls ends the game
- Collision detection with the snake's own body ends the game
- Smooth keyboard controls for movement (Arrow keys and WASD)
- Visual feedback with a game over message

## Requirements

- Python 3.8 or newer (the turtle module is included in the standard library)

## Installation

1. Clone or download this repository to your machine.

2. No additional dependencies required! The game uses Python's built-in `turtle` graphics library.

## Running the Game

To run the game, simply execute:

```bash
python main.py
```

## How to Play

- The snake starts moving automatically
- Use **Arrow keys** (Up, Down, Left, Right) or **WASD** keys to control the snake's direction
- Eat the red food circles to grow longer and increase your score
- Avoid hitting the walls or your own tail
- Click anywhere on the screen to exit after game over

## Controls

- **↑** or **W** - Move up
- **↓** or **S** - Move down
- **←** or **A** - Move left
- **→** or **D** - Move right

## Game Rules

- The snake cannot move backward into itself (180-degree turns are prevented)
- Each food item eaten increases your score by 1 and adds a segment to the snake
- Game ends if the snake hits any wall boundary
- Game ends if the snake collides with its own body

## Project Structure

```
Snake Game/
├── main.py       # Main game file with Snake, Food, and Scoreboard classes
└── README.md     # This file
```

## Code Overview

The game consists of three main classes:

- **Snake**: Manages the snake's segments, movement, and direction
- **Food**: Randomly places food on the screen for the snake to eat
- **Scoreboard**: Tracks and displays the current score and game over message

## Troubleshooting

- If the game window doesn't open, ensure you're running Python 3.8 or newer
- On some systems, you may need to have Tk/Tcl installed (usually comes with Python)
- If the game is too fast or slow, modify the `time.sleep(0.1)` value in main.py

## Future Enhancements

Possible improvements to consider:

- Add a high score system that persists between sessions
- Implement difficulty levels (faster speed as score increases)
- Add sound effects
- Create a pause/resume feature
- Add a restart button to play again without closing the window

## License

This is an open-source educational project. Feel free to use and modify as needed.

## Credits

Built with Python's turtle graphics library.

Created by you — enjoy building your Snake game!
