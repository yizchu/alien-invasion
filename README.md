# Alien Invasion

A fast-paced, open-source 2D arcade shooter where the player defends Earth from waves of alien invaders. This project is designed for fun, learning, and easy modification — perfect for game jam entries, tutorials, or as a starting point for your own shooter.

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Run the Game](#run-the-game)
- [Gameplay & Controls](#gameplay--controls)

## Features
- Fast-paced arcade-style gameplay with progressive enemy waves
- Multiple enemy types
- Score, lives, and basic power-ups
- Easy-to-read codebase intended for learning and extension
- Configurable settings for difficulty and controls

## Getting Started

### Prerequisites
This project is intentionally generic. Replace these instructions with the exact commands for your project's tech stack.

Common examples:
- For Python/Pygame: Python 3.8+ and pip
- For HTML5/Phaser: Node.js and a static server (or host on GitHub Pages)
- For Unity: Unity Editor (version X.Y) and Unity Hub

### Installation
Clone the repository:
```bash
git clone https://github.com/yizchu/alien-invasion.git
cd alien-invasion
```

Install dependencies (examples — choose the one that matches your project):

Python / Pygame example:
```bash
python -m venv venv
source venv/bin/activate   # macOS / Linux
venv\Scripts\activate      # Windows
pip install -r requirements.txt
```

JavaScript / Phaser example:
```bash
npm install
```

Unity:
- Open the project in Unity Hub and let the editor import assets and packages.

### Run the Game
Python / Pygame:
```bash
python main.py
```

JavaScript (dev server):
```bash
npm run start
# or
npx http-server ./ -p 8080
# then open http://localhost:8080 in your browser
```

Unity:
- Press Play in the Unity Editor.

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
