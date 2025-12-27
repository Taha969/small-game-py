 # **🐍Classic Snake Game**

Welcome to the Snake Game project, developed in Python using the Pygame library.This project is a modern implementation of the timeless classic,
where the player controls a snake that grows in length as it consumes food,challenging the user to avoid walls and its own body.

# 📖 About the Project

This game is designed to be both simple and engaging, focusing on core game development concepts such as:
   
   ⚪ Dynamic Movement: Real-time response to keyboard inputs.
   
   ⚪ Growth System: The snake increases in length with every "food" item consumed.
    
   ⚪ State Management: Handling "Game Over," "Reset," and "Quit" states.
    
   ⚪ Visuals: A clean UI featuring a blue background, a green snake, and red food blocks.

# ⚙️ Prerequisites

To run this game smoothly, ensure you have the following installed:

  ⚪ Python 3.x: The core programming language.

  ⚪ Pygame Library: The framework used for graphics and event handling.

You can install the required library via Terminal/Command Prompt using:
Bash

pip install pygame

🚀 Installation & Execution

    Download the Script: Save the code as a Python file (e.g., snake_game.py).

    Open Terminal: Navigate to the directory containing the file.

    Run the Game: Execute the following command:

Bash

python snake_game.py

🧠 Code Logic & Architecture

The script is structured into modular functions to ensure clean and readable code:
1. Initialization & Configuration

    pygame.init(): Initializes all imported pygame modules.

    Global Variables: Defines screen dimensions (800×600), colors (RGB format), and game physics (Snake speed and block size).

2. The Game Loop (gameLoop)

This is the heart of the application. It runs continuously until the player quits or loses. It manages:

    Event Handling: Monitors keystrokes to update the snake's direction.

    Collision Detection: Checks if the snake hits the boundaries or its own tail.

    Coordinate Updates: Calculates the new position of the snake head and shifts the body accordingly.

    Food Generation: Uses the random module to spawn food at aligned grid coordinates after each meal.

3. Utility Functions

    our_snake: Iterates through the list of coordinates to render each segment of the snake on the screen.

    message: Renders text on the screen to communicate the game status to the player.

🎮Controls Summary
Key	           Action
⬆️ Up Arrow 	Move Up
⬇️ Down Arrow	Move Down
➡️ Right Arrow	Move Right
⬅️ Left Arrow	Move Left
Q	 Quit Game (on Game Over screen)
C	 Play Again (on Game Over screen)

🛠️ Built With

    Python - Logic and Structure.

    Pygame - Multimedia and Graphics engine.

    Random - Randomized food positioning.
