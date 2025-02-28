# Task-2: TIC-TAC-TOE AI

The Python code implements a Tic-Tac-Toe game where a player competes against an AI opponent.

IMPORTS :

The random module is used for generating random moves.

GAME INSTRUCTIONS:

The instructions variable explains the game rules and board format.

BOARD INITIALIZATION :

The sign_dict list represents the board with nine empty spaces.

FUNCTIONS :

1) print_board(): Displays the current board state.

2) take_input(): Prompts the player for a move and validates it.

3) is_moves_left(): Checks if any empty spaces are left on the board.

4) evaluate(): Checks if a player (X or O) has won the game by evaluating possible win 5)conditions (rows, columns, and diagonals).

6) minimax(): Implements the Minimax algorithm for the AI to make optimal moves.

7) find_best_move(): Uses the Minimax algorithm to find the best move for the AI.

MAIN FUNCTION :

Orchestrates the Game Flow:

Welcomes the player and displays instructions.
Prompts the player for their name and assigns signs (O for the player, X for the AI).
Alternates turns between the player and AI, using the Minimax algorithm for AI moves and take_input() for player moves.
Prints the board after each move and checks for win conditions.
Declares the winner or a tie based on the game outcome.

Finally,The game runs until either the player or AI wins, or the board is full, resulting in a tie.

