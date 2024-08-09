# Snake Game

Welcome to the Snake Game! This classic game has been recreated using HTML, CSS, and JavaScript, providing players with a fun and interactive experience. This README file will guide you through the features and functionality of the game, as well as how to set it up locally.

## Table of Contents
1. [Introduction](#introduction)
2. [Technologies Used](#technologies-used)
3. [Game Features](#game-features)
4. [How to Play](#how-to-play)
5. [Setup Instructions](#setup-instructions)

## Introduction
The Snake Game is a simple yet addictive game where the player controls a snake that grows as it consumes food. The objective is to grow the longest snake possible without crashing into the walls or itself. 

## Technologies Used
- **HTML**: To structure the game interface.
- **CSS**: For styling and layout of the game board and elements.
- **JavaScript**: To handle game logic, user input, and game state.

## Game Features

- **Responsive Gameplay**: The game is designed to be responsive across different devices and screen sizes.
- **Collision Detection**: Detects collisions with walls and the snake itself, leading to game-over scenarios.
- **Score Tracking**: Keeps track of the player's score, updating as the snake consumes food.
- **High Score Storage**: Utilizes `localStorage` to save the highest score, allowing players to track their best performance.
- **Sound Effects**: Incorporates sound effects for actions such as moving, eating food, and game-over scenarios.
  
## How to Play

1. **Starting the Game**: Press any key to begin once the game has loaded.
2. **Controlling the Snake**:
   - Use the arrow keys to control the direction of the snake:
     - **Arrow Up**: Move up
     - **Arrow Down**: Move down
     - **Arrow Left**: Move left
     - **Arrow Right**: Move right
3. **Goal**: Eat the food that appears on the board to increase your score and make the snake longer.
4. **Game Over**: The game ends if the snake collides with the walls or itself. After a game over, a prompt will appear to restart the game.

## Setup Instructions

To run the Snake Game locally, follow these steps:

1. **Clone the repository** or download the code files to your local machine.
2. **Open the `index.html` file** in your web browser. You can do this by dragging the file into your browser or right-clicking and selecting 'Open with'.
3. Ensure that you have the sound files (`food.mp3`, `gameover.mp3`, `move.mp3`, `music.mp3`) available in the same directory as your HTML file for the sound effects to work.
4. Press any key to start the game and enjoy!

Thank you for checking out the Snake Game! Enjoy playing and may you achieve the highest score!
