# AI-Powered-Tic-Tac-Toe-Game-using-Minimax-with-Alpha-Beta-Pruning
This repository contains a complete implementation of the Tic-Tac-Toe game (3x3 grid) with an AI agent that uses the Minimax algorithm enhanced by Alpha-Beta Pruning to play optimally. This means the AI will never lose and will always choose the best possible move given the current state of the board.

📝 Problem Statement
Tic-Tac-Toe, also known as noughts and crosses or Xs and Os, is a classic two-player game played on a 3×3 grid. Players take turns marking the spaces with their respective symbols — X or O. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game.

The goal of this project is to implement an AI-powered Tic-Tac-Toe game using the Minimax algorithm enhanced with Alpha-Beta Pruning. The AI must evaluate the game board and return the optimal move for the current player, ensuring a perfect strategy that never loses.

Game Rules
Two players: one uses X, the other uses O.
Players alternate turns.
The player who places three of their marks in a row, column, or diagonal wins.
If all cells are filled without a winner, the game ends in a draw.

Functions Implemented
initial_state()
Initializes the empty 3x3 board.

player(board)
Returns whose turn it is — either 'X' or 'O'.

actions(board)
Returns the set of valid moves available on the current board.

result(board, action)
Returns a new board state after making a given move.

winner(board)
Returns the winner, if there is one.

terminal(board)
Checks if the game is over.

utility(board)
Returns:

+1 if 'X' wins
-1 if 'O' wins
0 for a draw

alpha_beta_pruning(board)
Core function that uses the Minimax algorithm with Alpha-Beta Pruning to return the best move for the current player.


