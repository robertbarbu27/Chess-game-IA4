# Chess Game

This project is a  implementation of a chess game, written in Python. It consists of two main files: `chessmain.py` and `chessengine.py`. The game has fully functionalities of a chess game, including stalemate, en-passant moves and castling moves. We have also tried to do an mini AI 
but it worked really bad and we decided not to present it.
For the developing of this project we are planning to do an ELO rating for every user, and try to 
do this multiplayer.
We have also functionalities of undo the move with Z and refresh the game with R.

## Contributions
Barbu Robert - Game mechanics
Dinu Florin - The flow of the game
Chipuc Valentin - Game mechanics


## Main Dificulties
The main dificulty was working with python because none of us did before, and we were not familiar
with syntax for clases, indentation, and functions.
Another dificulty was the animation of the game, we didn't exactly know how this animations works,
but after some small tutorials on youtube, we figured it out.
The mechanics of the game also were not easy. Thing like en_passant_moves, pinned pieces, check all valid moves were not piece of cake, but we were two responsibles with mechanics so after some discussions things worked properly. 

Estimated time of the project:
    We did it during five days, We estimate somewhere around 15-20 working hours, (including documentation for the game and tutorials). We also did a text editor but we decide that the chess game is nicer:)).



## chessmain.py

This is the main file that runs the game. It sets up the game board, handles user input, and manages the game state.

## chessengine.py

This file contains the logic for the chess engine. It includes the rules for each piece's movement, checks for check and checkmate conditions, and handles the game's logic.

## technologies

We used pygame for the graphic of the game, none of us was experienced with python, we also did a text editor but something quite simple and we all love to play chess so we decided to do a chess game

## How to Run

To run the game, simply execute the `ChessMain.py` file in a Python environment.

```bash
python ChessMain.py