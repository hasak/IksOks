# IksOks

A console-based Tic-Tac-Toe game written in C++. It supports:

* **Single-player mode:** Play against the computer with a simple AI.
* **Two-player mode:** Play against another human player.
* **Score tracking:** Displays running score for both players.
* **Interactive console UI:** Visual 3x3 board updated after each move.

## Features

* Uses ASCII art for board visualization.
* Simple AI logic that blocks or wins when possible, otherwise plays randomly.
* Dynamic handling of player names.
* Keeps running score until the game is closed.

## Usage

1. Compile the code with a C++ compiler (e.g., `g++ IksOks5.cpp -o tictactoe`).
2. Run the executable.
3. Choose mode:

   * `1` for playing against the computer
   * `2` for two-player mode
   * `3` to exit
4. Follow on-screen instructions to make moves (keys `1-9` correspond to board positions).

## Notes

* Ensure the console window is large enough to properly display the board.
* AI is simple but can handle basic blocking and winning moves.
* Works on Windows due to `conio.h` and `windows.h` usage.

