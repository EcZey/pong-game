# Pong Game

Welcome to the Pong Game! This project is a classic Pong game implemented using Python's `turtle` graphics library. Enjoy playing this two-player game where you control paddles to hit the ball and score points.

## Project Overview

This project simulates the classic Pong game. It features:
- Two paddles controlled by players.
- A ball that bounces off paddles and walls.
- A scoreboard to track points for each player.

## Features

- **Two Paddles**: Controlled by the keyboard.
- **Ball Movement**: The ball bounces off the walls and paddles.
- **Scoring System**: Points are awarded when the ball passes a paddle.
- **Game Controls**:
  - Player 1 (Right Paddle): Use the Up and Down arrow keys.
  - Player 2 (Left Paddle): Use the 'W' and 'S' keys.

## Requirements

- Python 3.10 or newer (Tested with Python 3.12)
- `turtle` module (comes with Python standard library)

## Usage

1. **Run the Game**:
   Execute `python main.py` to start the game.

2. **Controls**:
   - **Player 1**: 
     - **Up Arrow**: Move right paddle up.
     - **Down Arrow**: Move right paddle down.
   - **Player 2**: 
     - **W**: Move left paddle up.
     - **S**: Move left paddle down.

3. **Scoring**:
   - Points are scored when the ball passes one of the paddles.
   - The score is updated on the screen.

4. **Exiting the Game**:
   - Click on the window to exit the game.

## Code Structure

- **`main.py`**: The main file that runs the Pong game.
- **`ball.py`**: Contains the `Ball` class that manages the ball's movement and behavior.
- **`paddle.py`**: Contains the `Paddle` class that manages the paddles' positions and movement.
- **`scoreboard.py`**: Contains the `Scoreboard` class that handles scoring and displays the score.

## Object-Oriented Programming

This project utilizes Object-Oriented Programming (OOP) principles to structure the game:
- **Encapsulation**: The `Ball`, `Paddle`, and `Scoreboard` classes encapsulate related data and behavior.
- **Inheritance**: The `Ball` and `Paddle` classes inherit from the `Turtle` class to utilize turtle graphics functionality.
- **Modularity**: The code is organized into separate modules for clarity and reusability.
