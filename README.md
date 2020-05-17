# Game_of_Life

> Python implementation of Conway's Game of Life 🕹️

Conway's Game of Life is all about simulating real life rules on some random arrangement of cells in a given environment. The rules are as follows.
## Ruleset

Using the following ruleset the 2D grid of cells will evolve from generation to generation until it reaches a static state of either all dead cells or a mix of still, oscillating, or moving (spaceship) cells.

1. _**Underpopulation**_ - If a live cell has is surrounded by less than two surrounding neighbours it dies and does not make it to the next generation.
2. _**Equilibrium**_ - If a live cell is surrounded by two or three living neighbors the cell stays alive and makes it to the next generation.
3. _**Overpopulation**_ - If a live cell is surrounded by more than three living neighbors the cell dies and does not make it to the next generation.
4. _**Reproduction**_ - If a dead cell is surrounded by three living neighbors the cell stays alive and makes it to the next generation.

The **`game of life.ipynb`** code in this repository follows random arrangement of cells first and you have to prive the no. of generations you  want to print and the board should be "alive" after that.
