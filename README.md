# Asteroid Game

This is a simple asteroid game built using Python and Pygame. The player controls a spaceship that can shoot bullets to destroy asteroids. Large asteroids split into smaller asteroids when hit, and the game ends if the player collides with an asteroid.

## Features

- Player can rotate and move the spaceship using the keyboard.
- Player can shoot bullets to destroy asteroids.
- Large asteroids split into medium asteroids, and medium asteroids split into small asteroids.
- Game ends if the player collides with an asteroid.

## Controls

- `W`: Move forward
- `S`: Move backward
- `A`: Rotate left
- `D`: Rotate right
- `SPACE`: Shoot

## Installation

1. Clone the repository:

git clone https://github.com/Raterfy/Asteroid.git
cd asteroid-game

2. Create a virtual environment and activate it:

python -m venv .venv
source .venv/bin/activate
On Windows use `.venv\Scripts\activate`

3. Install the dependencies:

pip install -r requirements.txt

4. Run the game:

python main.py
On windows use `python .\main.py`