# Alien Invasion

A fast-paced, open-source 2D arcade shooter where the player defends Earth from waves of alien invaders. This project is designed for fun, learning, and easy modification — perfect for game jam entries, tutorials, or as a starting point for your own shooter.

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Run the Game](#run-the-game)
- [Gameplay & Controls](#gameplay--controls)

## Features
- Fast-paced arcade-style gameplay with progressive enemy waves
- Multiple enemy types
- Score, lives, and basic power-ups
- Easy-to-read codebase intended for learning and extension

## Getting Started

### Installation
Clone the repository:
```bash
git clone https://github.com/yizchu/alien-invasion.git
cd alien-invasion
```

### Run the Game
Python / Pygame:
```bash
python main.py
```

## Gameplay & Controls
Default controls (update to match actual controls in your project):
- Move left / right: Arrow keys or A / D
- Shoot: Spacebar or Left mouse button
- Pause: P or Esc

Objective:
- Survive waves of aliens, earn points by destroying enemies, and try to beat your high score.
- Collect power-ups for temporary advantages (e.g., rapid fire, shields).

```
## Development
- Keep game logic modular: separate player, enemy, projectile, and UI code.
- Add new enemy behavior by creating a new enemy class and registering it into the wave spawner.
- Improve performance by batching sprite draws and limiting active particle effects.

Suggested workflow:
1. Create a feature branch: `git checkout -b feat/new-enemy`
2. Implement and test locally
3. Open a Pull Request with a clear description and screenshots/GIFs of changes
4. Request review and merge when approved

For questions, suggestions, or contributions, open an issue or contact the repository owner: yizchu.

Happy hacking — shoot some aliens!
