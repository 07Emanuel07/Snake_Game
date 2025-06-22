# Snake Game Project

This Python application utilizes the `turtle` module to create an interactive version of the classic Snake game. 
Players control a snake that moves around the screen, eating food to grow longer while avoiding collisions with the walls and itself.

## Key Features

**Game Setup with Turtle Graphics:**
  - The game uses the `turtle` module to create a graphical window where the game takes place. The screen is set up with a specified width and height.

**Snake Class:**
  - The `Snake` class defines the snake's behavior, including movement, growth and resetting the snake when it collides with itself or the wall.

**Food Class:**
  - The `Food` class defines the food that the snake eats. The food appears at random positions on the screen.

**Scoreboard Class:**
  - The `Scoreboard` class tracks the player's score and updates the display whenever the snake eats food.

**Game Logic and Controls:**
  - The main game loop updates the screen, moves the snake and checks for collisions with the food, walls and itself. User input is handled to control the snake's direction.
