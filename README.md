# Python-s-Classic-Snake-Game
This is a classic Snake Game built using Python's Turtle module. The snake moves around the screen, eating food, and growing in size. The goal is to get the highest score by consuming as much food as possible without colliding with the walls or the snake's own tail.

# Files Overview
* [```1. main.py```](https://github.com/balajimanilal/Python-s-Classic-Snake-Game/blob/main/main.py)
This is the entry point of the game. It initializes the game screen, sets up keyboard controls, and runs the game loop, which checks for collisions and updates the game state.

* [```2. snake.py```](https://github.com/balajimanilal/Python-s-Classic-Snake-Game/blob/main/snake.py)
This file contains the Snake class, which handles the creation and movement of the snake, as well as its growth when it eats food. It also manages the direction changes based on user input.

* [```3. food.py```](https://github.com/balajimanilal/Python-s-Classic-Snake-Game/blob/main/food.py)
The Food class is responsible for generating food at random locations on the screen. Each time the snake eats the food, new food is placed elsewhere.

* [```4. scoreboard.py```](https://github.com/balajimanilal/Python-s-Classic-Snake-Game/blob/main/scoreboard.py)
This file defines the Scoreboard class, which tracks and displays the current score. It also shows a "GAME OVER" message when the game ends.

# How to Play
- Run the main.py file.
- Control the snake using the arrow keys:
- Up Arrow to move up
- Down Arrow to move down
- Left Arrow to move left
- Right Arrow to move right
- Eat the food to grow the snake and increase your score.
- Avoid hitting the walls or the snake's own tail.

> # Features
> - The game starts with a small snake that moves automatically.
> - Players control the snake using the arrow keys (Up, Down, Left, Right).
> - Every time the snake eats food, it grows longer and the score increases.
> - If the snake collides with the wall or its own tail, the game is over, and the score is displayed.
