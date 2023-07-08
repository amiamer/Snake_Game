# Snake Game

This is a simple implementation of the classic Snake game in C++.

## Introduction

The Snake game is a popular arcade game where the player controls a snake that moves around a rectangular grid. The objective is to eat food items (represented by 'X') to grow longer while avoiding collisions with the walls or the snake's own body. As the snake eats more food, it grows in length, making the game more challenging.

## Project Details

The project consists of the following files:

- `main.cpp`: This file contains the main implementation of the Snake game, including the game logic, rendering, and user input handling.
- `conio.h`: This header file provides functions for console input and output operations.
- `windows.h`: This header file provides functions for Windows API operations, such as clearing the console screen and using the `Sleep` function.
- `README.md`: A markdown file containing information about the project.

## How to Run

To run the Snake game, follow these steps:

1. Set up a C++ development environment with a compiler (e.g., Visual Studio, GCC).
2. Create a new C++ project and add the `main.cpp` file to the project.
3. Build and run the project.
4. The game will start in the console window, and you can use the following controls to play the game:
   - 'a': Move the snake left.
   - 'd': Move the snake right.
   - 'w': Move the snake up.
   - 's': Move the snake down.
   - 'x': Quit the game.

## Game Rules

- The snake starts in the center of the grid and initially has a length of 1.
- The snake moves continuously in the last input direction until a new direction is chosen.
- The objective is to eat the food items (X) that appear randomly on the grid.
- Each time the snake eats a food item, its length increases, and the player earns 10 points.
- The game ends if the snake collides with the walls or its own body.
- The player's score is displayed at the top of the console window.

## Customization

You can customize the game by modifying the following variables in the `main.cpp` file:

- `width`: Width of the game grid.
- `height`: Height of the game grid.
- `Sleep(30)`: Adjust the sleep duration (in milliseconds) between game frames for controlling the game speed.

Feel free to explore and modify the code to enhance the game or add new features!

## Acknowledgments

This Snake game implementation is based on a simple console-based game design. It serves as a beginner-level project to understand basic game development concepts in C++.

Enjoy playing the Snake game!
