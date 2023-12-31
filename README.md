﻿# Minesweeper

## Minesweeper Game and AI

This is a Python implementation of the classic Minesweeper game along with an AI player that can play the game. The game is played on a grid where the player must uncover cells that do not contain mines and mark cells that do contain mines. The goal is to uncover all safe cells without hitting a mine.

Table of Contents

1. Minesweeper AI
2. Game Controls
3. Running the Game
4. Minesweeper Game

# Minesweeper Game

The Minesweeper class represents the Minesweeper game. It allows you to create a game board with a specified height, width, and number of mines. You can interact with the game by revealing cells and marking mines.

- print(): Print a text-based representation of the game board.
- is_mine(cell): Check if a given cell contains a mine.
- nearby_mines(cell): Count the number of mines adjacent to a given cell.
- won(): Check if the player has successfully flagged all the mines.

# Minesweeper AI
- The MinesweeperAI class represents the AI player for Minesweeper. It uses logical reasoning to make safe moves and avoid mines.

- add_knowledge(cell, count): Update the AI's knowledge based on a revealed cell and its neighboring mine count.
- make_safe_move(): Return a safe cell to choose on the Minesweeper board, known to be safe and not already chosen.
- make_random_move(): Return a random move on the board that hasn't been chosen and is not known to be a mine.

# Game Controls
- Left-click: Reveal a cell.
- Right-click: Mark a cell as a mine.
- AI Move: Let the AI make a move.
- Reset: Start a new game.

# Running the Game
- Ensure you have the required libraries installed, such as Pygame.
- Run runner.py to start the Minesweeper game.
- Follow the on-screen instructions to play the game manually or use the AI player for assistance.


Have fun playing Minesweeper with the option to let the AI help you uncover the mines safely!
