# Ping Pong

**Ping Pong** is a fast-paced two-player arcade game built using Python and Pygame. This digital version of the classic table tennis game offers smooth controls, ball physics, collision handling, and a dynamic scoring system.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Running the Game](#running-the-game)
- [Controls](#controls)
- [Gameplay](#gameplay)
- [License](#license)

---

## Features

- 2-player local game (Player 1 vs Player 2)
- Realistic ball bounce mechanics and speed acceleration
- Smooth paddle control with bounds checking
- Dynamic scoring and win screen
- Stylized UI with score display and center dashed line
- Reset functionality after each round

---

## Tech Stack

- **Language:** Python 3
- **Library:** [Pygame](https://www.pygame.org/) `v2.6.0`

---

## Getting Started

### Installation

1. Clone the repository:

```bash
git clone https://github.com/SidoJain/Ping-Pong.git
cd Ping-Pong
```

2. Install dependencies using pip:

```bash
pip install -r requirements.txt
```

### Running the Game

Run the main game script:

```bash
python main.py
```

## Controls

- Left Player (Paddle 1):
    - `W` - Move Up
    - `S` - Move Down
- RIght Player (Paddle 2):
    - `↑` Arrow Key - Move Up
    - `↓` Arrow Key - Move Down

## Gameplay

- The first player to reach a score of 10 wins.
- The ball increases speed after paddle hits.
- A message is displayed for the winning player.
- After a round, the game resets automatically for replay.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).