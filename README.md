# Tic Tac Toe Game

A simple and interactive Tic Tac Toe game built using JavaScript, HTML, and CSS. This game is perfect for two players who want to enjoy a quick and classic game of Tic Tac Toe directly in their browser.

## Features

- **Two-Player Mode**: Play against a friend in this classic 3x3 grid game.
- **Dynamic UI Updates**: Click on the grid to place your mark ('X' or 'O') and see the changes immediately.
- **Winner Detection**: The game automatically detects a winner or a draw and displays a message.
- **Easy Reset**: Start a new game at any time with the click of a button.
- **Responsive Design**: Enjoy the game on any device, whether it’s a desktop or mobile.

## How to Play

1. **Player Turn**: Players take turns clicking on an empty box to place their mark ('O' or 'X').
2. **Win Conditions**: The first player to align three of their marks in a row, column, or diagonal wins the game.
3. **Draw**: If all boxes are filled without any player aligning three marks, the game ends in a draw.
4. **Reset**: Click the "New Game" or "Reset" button to start a new match.

## How It Works
The game uses basic JavaScript to handle user interactions and game logic:

-**Event Listeners:** Each box in the grid has an event listener that detects clicks and places the appropriate mark.
-**Turn Tracking:** A boolean flag (turnO) keeps track of whose turn it is.
-**Win Detection:** The game checks all possible winning combinations after each turn to determine if there is a winner.
-**Draw Condition:** If all nine boxes are filled and there is no winner, a draw is declared.
-**Game Reset:** The "Reset" and "New Game" buttons clear the board and reset all variables.

##Technologies Used
**HTML:** For the game structure.
**CSS:** For styling the game interface.
**JavaScript:** For game logic and interactivity

**Thanks to all contributors and players who have enjoyed this classic game!**
