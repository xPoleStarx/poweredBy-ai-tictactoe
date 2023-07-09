# Tic-Tac-Toe Game with AI

This is a simple implementation of the Tic-Tac-Toe game with an AI opponent using the minimax algorithm. The game is built using the Pygame library in Python.

## Requirements

- Python 3.x
- Pygame library

## How to Run

1. Make sure you have Python 3.x installed on your system.
2. Install the Pygame library by running the following command:
   ```
   pip install pygame
   ```
3. Download the `runner.py` and `tictactoe.py` files from this repository.
4. Open a terminal or command prompt and navigate to the directory where the downloaded files are located.
5. Run the game by executing the following command:
   ```
   python runner.py
   ```
6. The game window will open, and you can start playing Tic-Tac-Toe against the AI opponent.

## Gameplay Instructions

1. When the game starts, you will see the title "Play Tic-Tac-Toe" and two buttons: "Play as X" and "Play as O".
2. Click on one of the buttons to choose whether you want to play as "X" or "O".
3. Once you have made your selection, the game board will be displayed.
4. You can make a move by clicking on an empty tile on the board.
5. The AI opponent will automatically make its move after you make yours.
6. The game will continue until there is a winner or a tie.
7. If the game is over, you will see a message indicating the result.
8. To play again, click the "Play Again" button at the bottom of the screen.

## AI Algorithm - Minimax

The AI opponent in this game uses the minimax algorithm to determine the best possible move. Minimax is a recursive algorithm that explores all possible moves and assigns a score to each move based on the resulting game state. The AI selects the move with the highest score when it is its turn to play.

## Credits

- This project was created by Seyfullah Korkmaz.
- The Pygame library is used for creating the game interface.
- The minimax algorithm is used for the AI opponent.

Feel free to modify and enhance this project according to your needs. Enjoy playing Tic-Tac-Toe!
