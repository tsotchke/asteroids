# Asteroids Game in C

## Overview

This is a simple implementation of the classic Asteroids game, written in C. The game runs entirely in the terminal, allowing players to navigate a spaceship, shoot asteroids, and avoid collisions. It showcases fundamental game mechanics while providing an engaging user experience for players of any age.

## Technical Qualities

- **Self-Contained**: The entire game is self-contained with no external dependencies. It uses standard libraries, making it easy to compile and run on any system with a C compiler.

- **Vector Graphics**: The game utilizes basic vector graphics techniques for rendering the spaceship, asteroids, and bullets. Functions are provided to draw pixels, lines, and circles directly in the terminal. These are drawn with ascii characters.

- **Efficient Game Loop**: The game loop is designed to run smoothly, updating the game state and redrawing the screen at a controlled frame rate (20 FPS). User input is handled asynchronously, allowing for responsive controls via the keyboard.

- **Collision Detection**: Basic collision detection is implemented to manage interactions between the spaceship and asteroids, as well as between bullets and asteroids, enhancing gameplay dynamics.

- **Scoring and Timing**: The game tracks the player's score and the elapsed time, providing feedback on performance. The timer stops upon game over, displaying the final score and time taken.

## Features

- **User Controls**:
  - Use arrow keys to maneuver the spaceship.
  - Press the spacebar to fire bullets.
  - Press 'q' to quit the game.
  - Press 'r' to restart after game over.

- **Dynamic Gameplay**: Randomly generated asteroids move around the screen, and the player must navigate and shoot them down while avoiding collisions.

- **Terminal-Based**: The game operates entirely within the terminal, making it lightweight and easy to compile and run on various platforms.

## Installation and Usage

### Prerequisites

- A C compiler (like `gcc`) installed on your system.

### Compilation

To compile the game, open your terminal and navigate to the directory containing the source code file. Then run the following command:

```bash
gcc -o asteroids asteroids.c -lm
```

### Running the Game

After successful compilation, you can run the game with:

```bash
./asteroids
```

### Controls

- **Arrow Keys**: Navigate the spaceship.
- **Spacebar**: Fire bullets.
- **'q'**: Quit the game.
- **'r'**: Restart the game after game over.

## Conclusion

This Asteroids game in C serves as both a fun recreational experience and a practical demonstration of game programming fundamentals. With its self-contained nature and minimal dependencies, it provides an excellent starting point for anyone interested in game development using C.