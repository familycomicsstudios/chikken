# Chikkin - A Strategy Board Game

## Overview

Chikkin is a two-player strategy board game played on an 8x8 chessboard. Players, designated as East and West, take turns moving their pieces. The goal is to outmaneuver the opponent using movement, positioning, and piece abilities.

## Setup

Each player begins with the following pieces:

- 8 Chickens (c/C) - Lined up in the second row.

- 6 Roosters (r/R) - Positioned on the edges of the first row.

-  1 Dog (d/D) - Placed in the left-middle of the first row.

- 1 Wolf (w/W) - Placed in the right-middle of the first row.

- East's bottom-left square is a1, with notation moving a-h (bottom to top) and 1-8 (left to right).

- East moves first.

## Movement Rules

### Chicken (c/C)

Moves one square per turn in any direction.

Cannot be pushed by any other piece.

### Rooster (r/R)

Moves to any square that can be reached without moving diagonally or passing through other pieces.

Can push one adjacent piece in the same direction as its movement. Pushing ends the Rooster's turn.

Cannot push a piece if it would be pushed into another piece.

### Dog (d/D)

Moves one square per turn in any direction.

Wins the game by reaching the opposite end of the board.

Can push any adjacent piece in any direction.

Cannot push a piece if it would be pushed into another piece.

### Wolf (w/W)

Moves one square per turn in any direction.

Removes Chickens and Roosters by moving into their square.

Cannot eat Dogs or other Wolves.

Moves one square per turn in any direction.

Removes Chickens and Roosters by moving into their square.

## Notation

c/C - Chicken (c for East, C for West)

r/R - Rooster

d/D - Dog

w/W - Wolf

Moves are recorded in chess notation, with the East player’s bottom-left square being a1.

## Victory Conditions

- Each player wins if their Dog (D) reaches the opposite row.

- Stalemate: If a player has no legal moves but is not in a losing position, the game ends in a draw, similar to Chess stalemate rules.

- Threefold repetition: If the same exact board position occurs three times, the game is a draw.

View the [full v1.0 rulebook](RULEBOOK.1.0.md) here to learn how to play in-depth.
