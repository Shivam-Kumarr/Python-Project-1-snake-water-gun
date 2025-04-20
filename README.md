# Snake Water Gun Game in Python

This is a simple implementation of the classic Snake Water Gun game in Python. You can play against the computer!

## How to Play

3.  **Enter your choice** when prompted. You can enter:
    * `s` for Snake
    * `w` for Water
    * `g` for Gun
4.  **See the result!** The computer will make its choice, and the outcome of the round will be displayed.

## Game Logic

The rules of the game are as follows:

* Snake beats Water
* Water beats Gun
* Gun beats Snake

The script uses a simple numerical representation for the choices:

* `1`: Snake
* `-1`: Water
* `0`: Gun

It then compares your choice with the computer's random choice to determine the winner.
