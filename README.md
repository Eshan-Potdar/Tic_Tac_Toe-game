# Tic Tac Toe

## Overview

Tic Tac Toe is a command-line game developed in Python where a player competes against a computer opponent.

The player uses the symbol **X** while the computer uses **O**. The game automatically checks for winning combinations across rows, columns, and diagonals after every move. If all positions are filled without a winner, the game ends in a tie.

This project demonstrates fundamental programming concepts including functions, loops, conditionals, lists, user input handling, and game logic.

## Features

* Player vs Computer gameplay
* Random computer move generation
* Win detection

  * Horizontal wins
  * Vertical wins
  * Diagonal wins
* Tie detection
* Console-based interface
* Input validation for occupied positions

## Technologies Used

* Python
* Random module

## Game Board Layout

Players select positions using numbers from 1 to 9.

```text
1 | 2 | 3
----------
4 | 5 | 6
----------
7 | 8 | 9
```

## How It Works

1. The player enters a position from 1 to 9.
2. The program places an **X** on the board.
3. The computer randomly selects an available position and places an **O**.
4. After each turn, the game checks for:

   * Horizontal wins
   * Vertical wins
   * Diagonal wins
   * Tie conditions
5. The game continues until a winner is found or the board is full.

## Running the Program

Run the following command:

```bash
python tic_tac_toe.py
```

## Example Gameplay

```text
X | - | -
----------
- | O | -
----------
- | - | X

Enter number 1-9:
```

## Learning Outcomes

This project helped develop skills in:

* Python programming
* Function design
* List manipulation
* Game state management
* Conditional logic
* Debugging and testing

## Future Improvements

* Smarter AI using the Minimax Algorithm
* Two-player mode
* Graphical User Interface (GUI)
* Score tracking system
* Difficulty levels

## Author

Eshan Potdar

