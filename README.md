# Snake-Game
## Introduction
Welcome to the Snake Game! This is a classic arcade-style game developed in Python using the Pygame library. The objective is to navigate the snake, collect food, and grow in size while avoiding collisions with the walls or the snake's own body.

## Features
1. Simple Controls: Move the snake in four directions using the arrow keys.
2. Dynamic Gameplay: The snake grows as it eats food, increasing the challenge.
3. Scoring System: Keep track of your score as you play.
4. Restart Option: Replay the game after losing.

## Prerequisites
To run the game, ensure you have the following:
1. Python (version 3.6 or higher recommended)
2. Pygame Library :- Install it via pip: "pip install pygame"

## How to Play
1. ### Start the Game: 
Run the script using Python: "python snake_game.py"

2. ### Game Controls:
Use the arrow keys to move the snake:
↑ - Move Up
↓ - Move Down
← - Move Left
→ - Move Right

3. ### Objective:
Collect the green food blocks to grow the snake.
Avoid colliding with the walls or yourself.

4. ### Game Over:
Upon losing, you can:
Press C to restart the game.
Press Q to quit.


## Scoring
Your score increases by 1 point for each food block the snake eats. The current score is displayed at the top left corner of the game window.

## Customization
1. Snake Speed: Modify the SNAKE_SPEED variable in the script to adjust the game difficulty:
SNAKE_SPEED = 15  /# Increase for faster gameplay/

2. Screen Dimensions: Update the WIDTH and HEIGHT variables for a larger or smaller game window:
WIDTH, HEIGHT = 600, 400 /# Default dimensions/

### Known Issues
The snake may turn into itself if quick successive arrow key presses are made.
Food may occasionally appear under the snake, making it instantly collectible.

### Acknowledgments
This game is inspired by the classic Snake game and developed as a fun programming exercise. Enjoy playing and happy coding!
