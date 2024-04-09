
# Tic-Tac-Toe Game 
This is a simple command-line implementation of the classic Tic-Tac-Toe game written in Dart. Players take turns marking spaces in a 3x3 grid, aiming to be the first to form a horizontal, vertical, or diagonal line of their symbol ('X' or 'O').
![image](https://github.com/Alekiie/Dart_week8/assets/96947422/e411ecf3-0929-4eb6-9655-1aa067a3d576)

## How to Play
1. Setup: Run the program in a Dart environment.

2. Gameplay:
    * Players alternate turns.
    * Each turn, a player selects an empty space on the board by entering a number from 1 to 9 corresponding to the position they want to mark.
    * The game continues until one player wins by getting three of their symbols in a row, column, or diagonal, or until the board is full (a draw).
3. Winning: The game declares a player as the winner when they successfully align three of their symbols in a row, column, or diagonal.
4. Draw: If all spaces on the board are filled without a winner, the game declares a draw.

# Code Structure
  * Main Function: The main() function initializes the game, manages player turns, and checks for a winner or draw.
  * Board Representation: The board is represented as a list of strings, with each element indicating the current state of a cell ('X', 'O', or empty).
  * Input Handling: Player moves are captured using standard input (stdin) and validated to ensure they are within the bounds of the board and on an empty space.
  * Printing the Board: The printBoard() function displays the current state of the board after each move.
  * Winning Condition Check: The checkWin() function examines the board to determine if there's a winner based on rows, columns, or diagonals.
## Usage
  * Ensure you have Dart installed on your system.
  * Copy the provided code into a Dart file (e.g., tic_tac_toe.dart).
  * Run the Dart file using the Dart SDK or an IDE that supports Dart development.
## Further Improvements
  * Enhance the user interface by adding colors or graphical elements 😝. 
  * Implement error handling for unexpected input types.
  * Add an option for players to choose their symbols ('X' or 'O').
  * Implement a computer player for single-player mode.
## Contribution
>. Contributions to this project are welcome. Feel free to fork the repository, make improvements, and submit pull requests.
