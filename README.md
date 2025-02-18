# Asteroid Game

Asteroid Game is a simple 2D space shooter built using Python and Pygame. The player controls a spaceship that must navigate through an asteroid field while avoiding collisions and shooting asteroids to survive.

## Features

- Player-controlled spaceship that moves and shoots.
- Randomly generated asteroid field.
- Collision detection between player, asteroids, and shots.
- Asteroids split into smaller pieces when hit.
- Game over condition when the player collides with an asteroid.

## Installation

### Prerequisites

- Python 3.x
- Pygame library

### Install Pygame

Run the following command to install Pygame:

```sh
pip install pygame
```

## Running the Game

Clone this repository and navigate to the project folder:

```sh
git clone https://github.com/yourusername/asteroid-game.git
cd asteroid-game
```

Run the game using:

```sh
python main.py
```

## Controls

- **WASD** – Move the spaceship
- **Spacebar** – Shoot
- **Escape** – Quit the game

## Project Structure

```plaintext
asteroid-game/
│-- main.py         # Entry point of the game
│-- constants.py    # Game constants (screen size, colors, etc.)
│-- player.py       # Player spaceship logic
│-- asteroid.py     # Asteroid behavior and collision handling
│-- asteroidfield.py# Generates the asteroid field
│-- shot.py         # Handles player shooting mechanics
│-- README.md       # Project documentation
```

## Future Improvements

- Add sound effects and background music.
- Implement power-ups.
- Add a scoring system.
- Introduce multiple levels of difficulty.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

Enjoy playing Asteroid Game! 🚀

