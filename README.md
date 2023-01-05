# Snake
A simple implementation of the classic game Snake in Python using the pygame library.

## Requirements
- Python 3.x
- pygame

## How to Run
1. Install pygame by running `pip install pygame`
2. Download or clone this repository
3. Navigate to the directory containing the Snake files
4. Run `python snake.py` to start the game

## How to Play
Use the arrow keys on your keyboard to control the direction of the snake. The snake will continue moving in its current direction until you change its direction. The goal of the game is to make the snake eat as many food blocks as possible without touching the edges of the screen or its own body. The snake will grow by one block each time it eats a food block. The game is over when the snake touches the edges of the screen or its own body, at which point your score (the length of the snake) will be displayed on the screen.

## Notes
- The game window is 720x480 pixels
- The snake and food blocks are 10x10 pixels
- The snake moves at a rate of 10 pixels per frame
- The game runs at a frame rate of 20 FPS
