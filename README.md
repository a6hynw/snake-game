

Snake-Game

Introduction:
The Snake game is a classic arcade game where the player controls a snake that grows longer as it eats food. 
The objective of the game is to navigate the snake around the screen, avoiding collisions with walls and the snake's own body, while trying to eat as much food as possible to score points


![Screenshot 2024-05-03 123752](https://github.com/a6hynw/snake-game/assets/137154614/3546f3b5-af6f-4c2c-869c-de74d084088a)


Game Mechanics:
In the Snake game implemented using Python and Tkinter, the player controls the movement of the snake using arrow keys or other specified keys. 
The snake starts as a single segment on the game board and moves in the direction specified by the player. 
As the snake moves, it leaves a trail of segments behind it, creating the illusion of a continuously moving snake.


Food and Growth:
Scattered throughout the game board are pieces of food that the snake can eat to grow longer. 
When the snake's head comes into contact with a piece of food, it consumes the food, and its length increases by one segment. 
The player earns points for each piece of food eaten, and the snake's speed may increase as it grows longer, making the game more challenging.


![Screenshot 2024-05-03 123829](https://github.com/a6hynw/snake-game/assets/137154614/3476c2a1-067a-4bba-ad50-81ff0e9b120e)


Game Over Conditions:
1. The snake collides with the walls of the game board.
2. The snake collides with its own body.
When either of these conditions occurs, the game ends, and the player's final score is displayed on the screen.


![Screenshot 2024-05-03 123952](https://github.com/a6hynw/snake-game/assets/137154614/f69c0006-4bf3-477e-b6f4-12b4cede9b79)


User Interface:
The game interface is created using the Tkinter library in Python, which provides a simple and intuitive way to create graphical user interfaces. 
The game board, snake, food, and score display are all rendered using Tkinter widgets and canvas elements, allowing for easy customization and control over the game's appearance




