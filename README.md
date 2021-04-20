# Conway's Game of Life

_A Python implementation from scratch_

## Game Overview

- A grid is composed of cells.
- Each cell is either in a _dead_ or _alive_ state.
- The state of neighboring cells determine a given cell's state in the next
  round (also called "generation").
  - If a cell is **alive**, in the next generation it will:
    - **Die** if there are fewer than 2 or more than 3 living neighbors
    - **Live** if there are exactly 2 or 3 living neighbors
  - If a cell is **dead**, in the next generation it will:
    - **Live** if there are exactly 3 living neighbors
