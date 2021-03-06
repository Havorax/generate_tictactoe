# generate_tictactoe
Tic-Tac-Toe board state generator (along with some heuristic calculations)

###

Recursively generates all 5478 legal game states for tic-tac-toe.

e.g. let X be 1 and O be -1

     then the board:
     
      1 |    |   
     ---+----+---
     -1 | -1 |   
     ---+----+---
      1 |  1 | -1
     
     is represented as:
     
     1 0 0 -1 -1 0 1 1 -1
     
## Heuristics

The provided C++ code has <strong>commented out</strong> heuristic calculation code, used to augment the generated data for use in machine learning programs.

The augmented dataset was used to prototpe a [weakly supervised training](https://arxiv.org/abs/1605.07723) program for [this checkers AI](https://github.com/Havorax/CheckersBot)

## Tool(s)

Just C++ 11 and the g++ compiler.
