# Asteroids

A simple Asteroids-style game built with Python and Pygame.

The player controls a spaceship, avoids incoming asteroids and destroys them by shooting projectiles. Larger asteroids split into smaller and faster pieces when hit.

This project was created as part of Boot.dev's **Build Asteroids using Python and Pygame** course.

## Features

- Player movement and rotation
- Projectile shooting with a cooldown
- Random asteroid spawning
- Circle-based collision detection
- Asteroids split into smaller pieces when destroyed
- Game over when the player collides with an asteroid
- Object-oriented game structure

## Controls

| Key | Action |
|---|---|
| `W` | Move forward |
| `S` | Move backward |
| `A` | Rotate left |
| `D` | Rotate right |
| `Space` | Shoot |

## Requirements

- Python 3
- Pygame

Install Pygame with:

```bash
pip install pygame
```

## Running the Game

Clone the repository and open the project directory:

```bash
git clone [<repository-url>](https://github.com/Tilro1707/AstroidShooter)
cd asteroidShooter
```

Start the game:

```bash
python main.py
```

On some systems, use:

```bash
python3 main.py
```

## Project Structure

```text
.
├── main.py            # Main game loop and collision handling
├── player.py          # Player movement, rotation and shooting
├── asteroid.py        # Asteroid behavior and splitting
├── asteroidfield.py   # Random asteroid spawning
├── shot.py            # Projectile behavior
├── circleshape.py     # Shared base class and collision detection
├── constants.py       # Game settings and balancing values
└── logger.py          # Game state and event logging
```

## What I Practiced

- Object-oriented programming
- Pygame sprite groups
- Game loop architecture
- Delta-time-based movement
- Event handling
- Collision detection
- Projectile systems
- Inheritance and polymorphism

## Possible Future Improvements

- Score system
- Multiple lives
- Start and game-over screens
- Sound effects
- Screen wrapping
- High-score saving
- Different asteroid types
