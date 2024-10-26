# Connect 4 Game

A command-line implementation of the classic Connect 4 game written in Python.

## Description

This program implements a two-player Connect 4 game where players take turns dropping their tokens (X or O) into a 6x7 grid. Players must strategically place their tokens to get four in a row horizontally, vertically, or diagonally while preventing their opponent from doing the same.

## Features

- Interactive command-line interface
- 6x7 game board (6 rows, 7 columns)
- Alternating turns between X and O players
- Available position display system
- Input validation for:
  - Valid column-row combinations
  - Gravity simulation (pieces fall to lowest available position)
  - Proper input format (e.g., "a1", "b2")
- Win detection for:
  - Horizontal connections
  - Vertical connections
  - Diagonal connections (both directions)
- Draw detection when board is full
- Option to play multiple games

## How to Play

1. The game starts with player X's turn
2. The program shows available positions for each turn
3. Enter position as "column-letter row-number" (e.g., "a1", "b3")
4. Columns are labeled 'a' through 'g'
5. Rows are numbered 1 through 6 (bottom to top)
6. Pieces automatically fall to the lowest available position in chosen column
7. Players alternate turns until someone wins or the game is a draw

## Board Layout
```
|  6  |     |     |     |     |     |     |     | 
--------------------------------------------------
|  5  |     |     |     |     |     |     |     | 
--------------------------------------------------
|  4  |     |     |     |     |     |     |     | 
--------------------------------------------------
|  3  |     |     |     |     |     |     |     | 
--------------------------------------------------
|  2  |     |     |     |     |     |     |     | 
--------------------------------------------------
|  1  |     |     |     |     |     |     |     | 
--------------------------------------------------
| R/C |  a  |  b  |  c  |  d  |  e  |  f  |  g  | 
--------------------------------------------------
```

## Game Rules
- Players must connect four of their tokens in a row
- Connections can be horizontal, vertical, or diagonal
- Pieces must be placed in the lowest available position in chosen column
- Game ends when either:
  - A player connects four tokens
  - The board becomes full (draw)

## Input System
- Input format: column letter + row number (e.g., "a1")
- Valid column letters: a through g
- Valid row numbers: 1 through 6
- System only allows placement in valid positions
- Available positions are displayed before each turn

## Error Handling
- Invalid inputs prompt for re-entry
- System only allows placement in available positions
- Clear feedback on available moves
- Input validation ensures proper game flow

## Author
Kuan Chen Chen

## Date
September 23, 2024

## Version
1.0
