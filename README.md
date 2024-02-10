# Tic-Tac-Toe Android App

Welcome to the Tic-Tac-Toe Android app! This simple and classic game allows two players to compete in a battle of Xs and Os. The game features a user-friendly interface and an intuitive design.


https://github.com/HatoryHanzo182/Tic-Tac-Toe/assets/55142468/3fd41e93-833f-44ae-affc-4bce1acd77be


## Table of Contents
- [Game Layout](#game-layout)
- [How to Play](#how-to-play)
- [Game Logic](#game-logic)
- [Result Dialog](#result-dialog)
- [Restarting the Game](#restarting-the-game)

## Game Layout
The game layout consists of a 3x3 grid where players can make their moves. The players are represented by "X" and "O" symbols. Additionally, there is a display showing the names and symbols of both players at the top of the screen.

### Playing Field
The playing field consists of a 3x3 grid of cells, each initially empty. Players take turns making moves by tapping on an empty cell, marking it with their respective symbol.

## How to Play
1. Player 1 starts the game, placing "X" in an empty cell.
2. Players take turns making moves, placing their symbol in an empty cell.
3. The game continues until one player gets three of their symbols in a row (horizontally, vertically, or diagonally) or until the board is full, resulting in a draw.

## Game Logic
The game logic is implemented in the `MainActivity` class. Here's a brief overview:

- `OnCellClick(int index)`: Handles the logic when a cell is clicked. It marks the cell with the current player's symbol, checks for a winner, and updates the current player.
- `CheckForWinner()`: Checks the current state of the board to determine if there is a winner.
- `IsBoardFull()`: Checks if the game board is full, resulting in a draw.

## Result Dialog
A custom `ResultDialog` is displayed when the game is over. It shows the result of the game, indicating which player wins or if it's a draw.

## Restarting the Game
After showing the result dialog, the game can be restarted by tapping the "Restart" button. This clears the board, allowing players to start a new game.

Feel free to enjoy playing Tic-Tac-Toe with your friends!
