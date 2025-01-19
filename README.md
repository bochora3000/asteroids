# Asteroids Game

A modern Python implementation of the classic **Asteroids** arcade game using **Pygame**. Navigate your spaceship, avoid incoming asteroids, and destroy them by shooting. Survive as long as you can!

## Features

- **Dynamic Asteroid Field**: Asteroids of varying sizes spawn at random intervals and edges of the screen.
- **Player Controls**: Rotate, move, and shoot to avoid and destroy asteroids.
- **Asteroid Splitting**: Destroyed asteroids split into smaller ones, adding more challenge.
- **Physics Simulation**: Smooth movement using vectors for position and velocity.

## Technologies Used

- **Python 3.10+**
- **Pygame 2.0+**

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/asteroids-game.git
   cd asteroids-game
   ```

2. Install dependencies:
   ```bash
   pip install pygame
   ```

3. Run the game:
   ```bash
   python main.py
   ```

## How to Play

- **Controls**:
  - `W`: Move forward
  - `S`: Move backward
  - `A`: Rotate left
  - `D`: Rotate right
  - `SPACE`: Shoot

- Avoid collisions with asteroids.
- Destroy asteroids to earn points. Larger asteroids split into smaller ones upon destruction.
- Survive as long as possible!

## File Structure

- **`main.py`**: Entry point for the game.
- **`player.py`**: Player class handling spaceship movement and shooting.
- **`asteroid.py`**: Asteroid class with collision splitting logic.
- **`asteroidfield.py`**: Handles spawning and management of the asteroid field.
- **`shot.py`**: Handles bullets fired by the player.
- **`constants.py`**: Defines game constants such as screen size, asteroid sizes, and player speed.
- **`circleshape.py`**: Base class for circular game objects.


## Contribution

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
