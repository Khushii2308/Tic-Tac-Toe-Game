# Tic Tac Toe Game 🎮
## Overview
This project is a simple Tic Tac Toe game implemented in C. It allows two players to play the game on a 3x3 board, taking turns to place the nmbers(0-9) as marks (X or O). The program checks for a winner or a draw and announces the result accordingly.

## Features
✅ Two-player mode: Players take turns making moves.

✅ Win detection: The game checks for winning conditions after each move.

✅ Draw detection: If all squares are filled without a winner, the game declares a draw.

✅ Simple interface: The board is displayed in the terminal with real-time updates.

✅ Error handling: Prevents invalid moves and asks players to enter a valid position.

## How to Play
1. Run the program in a C compiler (GCC recommended).
2. The game starts with Player 1 (X) and Player 2 (O).
3. Players enter a number (1-9) corresponding to an empty square.
4. The board updates with the player's mark (X or O).
5. The game continues until:
   
*A player wins (three marks in a row, column, or diagonal).

*The board is full, resulting in a draw.

*The winner (if any) is displayed, and the game ends.

## Installation & Compilation

### 1. Clone the Repository -
   
one https://github.com/yourusername/tic-tac-toe.git

cd tic-tac-toe

### 2. Compile the Code -
   
#### *Using GCC (Linux/macOS):

gcc tic_tac_toe.c -o tic_tac_toe

./tic_tac_toe


#### *Using Windows (MinGW GCC):

gcc tic_tac_toe.c -o tic_tac_toe.exe

tic_tac_toe.exe

## Usage

After running the compiled program:

1. Follow on-screen instructions.
2. Enter a valid number (1-9) to mark a position.
3. Check for a winner or play until a draw.
4. Restart the game manually if you want to play again.

## Code Explanation
1. The board is represented by a character array.
2. Players enter numbers (1-9) to place their mark (X or O).
3. checkwin() function determines if there's a winner or a draw.
4. board() function updates and displays the current state of the game.
5. The game loops until a winner is found or the board is full.
   
## Example Game Output

	Tic Tac Toe

Player 1 (X)  -  Player 2 (O)

  1 | 2 | 3
 -----------
  4 | 5 | 6
 -----------
 ## 7 | 8 | 9


Player 1, enter a number: 5

## Future Enhancements
🔹 Single-player mode (with AI opponent).

🔹 Graphical User Interface (GUI) version using C++.

🔹 Replay feature without restarting the program.

## Contributing
Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (feature-branch).
3. Commit your changes (git commit -m "Added a new feature").
4. Push to the branch and submit a pull request.

## Author
👨‍💻 Khushi Bansal

### Now you're all set to play Tic Tac Toe! 🏆 Have fun! 🎮
