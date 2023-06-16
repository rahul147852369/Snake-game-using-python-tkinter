# Snake Game

This is a simple implementation of the classic snake game using the Pygame library in Python.

## Game Description
The snake game is a 2D grid-based game where the player controls a snake. The objective of the game is to eat food items scattered throughout the grid while avoiding collisions with the walls and the snake's own body. As the snake eats food, its length increases, making it more challenging to navigate without colliding. The game ends if the snake collides with the walls or its own body.

## Requirements
- Python 3.x
- Pygame library

## Installation
1. Install Python from the official Python website: [Python Downloads](https://www.python.org/downloads/)
2. Install Pygame using pip:
   ```
   pip install pygame
   ```

## How to Play
1. Run the `snake_game.py` file.
2. The game window will open, displaying the snake and food items.
3. Control the snake using the arrow keys: up, down, left, right.
4. Eat the food items by guiding the snake towards them.
5. The snake's length will increase each time it eats food.
6. Avoid collisions with the walls and the snake's own body.
7. The game ends if the snake collides with any of these obstacles.
8. The score is displayed on the screen, representing the number of food items eaten.
9. When the game is over, a "Game Over" message is displayed, along with the final score.
10. Press the Enter key to restart the game.

## Customization
You can customize various aspects of the game according to your preferences:
- Adjust the size of the game window by modifying the `screen_width` and `screen_height` variables in the code.
- Change the colors of the snake, food, and background by modifying the respective color variables (`white`, `red`, `black`).
- Modify the game speed by changing the `fps` (frames per second) variable.

## Acknowledgements
This snake game implementation is based on the Pygame library, which provides the necessary functionality for creating games in Python.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

