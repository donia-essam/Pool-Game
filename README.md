# 2D Pool Game - Physics-Based Simulation with Pygame

A 2D pool (billiards) game built using Python and Pygame, featuring realistic physics-based ball movement, collision handling, and particle effects for immersive visuals.

---

## Features

- **Physics-Based Simulation:**
Realistic motion and collisions between balls and table boundaries.

- **Particle System:**
Subtle particle effects for collisions, pocketing, and cue strikes.

- **Interactive Gameplay:**
Aim, shoot, and control the cue ball using the mouse.

- **Custom Physics Engine:**
Handles friction, momentum transfer, and angle-based reflection without external physics libraries.

- **Smooth Animation:**
Optimised frame updates for fluid gameplay at high FPS.

---

## Gameplay Overview

- The player controls the cue ball.
- Click and drag to set shot direction and power.
- Release to strike and watch the physics simulation in action.
- Balls collide, bounce, and pocket dynamically.


---

## Controls
Action                 ->        Control
- Aim / Set Direction	   ->      Move the mouse
- Charge Shot Power	       ->    Click and drag backward
- Shoot	                   ->    Release left mouse button
- Reset Game	            ->     Press R

---


---

## Technical Highlights

- **Language:** Python
- **Library:** Pygame
- **Core Systems:**
- *Vector-based motion & collision resolution*
- *Particle system (collision sparks, pocket dust, cue impact)*
- *Friction & velocity decay simulation*
- *Object-oriented design (Ball, Cue, Table, Particle, GameManager)*

---

---

## Project Structure

```
pool_game/
│
├── main.py                 # Entry point of the game
├── physics.py              # Physics and collision handling
├── particle_system.py      # Particle effects
├── objects.py              # Ball, Cue, Table classes
├── assets/
│   ├── table.png           # Table texture
│   ├── cue.png             # Cue stick image
│   └── sounds/             # Optional hit/pocket sounds
└── README.md               # Project documentation
```

---

---
## Requirements

### Hardware
- A desktop or laptop with basic GPU support (no CUDA required).  

### Software
- **Python 3.7+**
- **Pygame library**

---

---

## Installation & Running

1. Clone the repository:
git clone https://github.com/donia-essam/Pool-Game.git
cd Pool-Game

2. Install dependencies:
pip install pygame

3. Run the game:
python main.py

---
