# Conway's Game of Life

_A Python implementation from scratch leveraging object-oriented principles_

## Game Overview

- A _grid_ is composed of _cells_.
- Each cell is either in a _dead_ or _alive_ state.
- The state of neighboring cells determine a given cell's state in the next
  round (also called "generation").
  - If a cell is **alive**, in the next generation it will:
    - **Die** if there are fewer than 2 or more than 3 living neighbors
    - **Live** if there are exactly 2 or 3 living neighbors
  - If a cell is **dead**, in the next generation it will:
    - **Live** if there are exactly 3 living neighbors

## Motivation

It's been a little while since I've needed to implement anything from scratch
using OOP, so I figured this would be good exercise to get some of the rust off.

(Also, I had heard more of the lore behind the game and its creator than what I knew
about the gameplay mechanics itself.)

## Notes

Please, do let me know if you have any feedback on how to do this in a more
Pythonic or elegant way -- I know the mechanism behind OOP, but I could use reps
in thinking through design and interface!
