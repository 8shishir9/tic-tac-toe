# Tic Tac Toe Game in C++

## Overview
This project is a simple implementation of the classic game Tic Tac Toe in C++. It is a two-player console game where players take turns marking a space in a 3x3 grid with their respective mark (X or O). The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game.

## Features
- Two-player game play on the same system.
- Simple and intuitive text-based interface.
- Automatic win/draw detection.
- Clear display of the game board and player turns.

## Getting Started

### Prerequisites
- A compiler that supports C++11 (e.g., GCC, Clang, MSVC).

### Compilation and Running
To compile and run the game, follow these steps:

1. Clone the repository or download the source code.
2. Open your terminal or command prompt.
3. Navigate to the directory containing the game's source code.
4. Compile the code. For example, using g++ you can compile the game with the following command:
   ```sh
   g++ -o TicTacToe TicTacToe.cpp
   ```
5.Run the compiled program
```
./TicTacToe
```
## How to play
The game starts with an empty 3x3 grid.
Players are prompted in turn to enter a number from 1 to 9, corresponding to different positions on the grid.
The game displays the updated grid after each move.
The game ends when one player wins by connecting three of their marks in a row, column, or diagonal, or when the grid is full and the game is a draw.
To play again, simply run the program again.
## Contributions
Contributions to the project are welcome! Please feel free to fork the repository, make your changes, and submit a pull request.
## License
This project is open-source and available under the MIT License
