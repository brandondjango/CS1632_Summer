### Exercise 1 - Unit Testing

Your goal in this exercise is to develop a command-line version of Conway's Game of Life.  This consists of an _n_ x _n_ matrix of cells, each of which can be either living (displayed with an `X`) or dead (displayed with a `.`).

The game shall go on for _m_ iterations.

The game shall accept four arguments: size, seed, percent, and max iterations.

The size argument shall represent the size of the matrix (size by size).  It shall be a square, not a rectangle.

The seed argument shall be the seed of the random number generator.

The percent argument shall be the percentage of cells that are alive for the initial iteration.

The max iterations argument shall be the number of iterations before the program ends.

Rules for iterating:

For each cell:

1. If cell is alive, then if two or three of its neighbors are alive, it shall remain alive during the next iteration.
2. If cell is dead, then if exactly three of its neighbors are alive, it shall be alive during the next iteration.
3. Otherwise, the cell shall be dead.

The program shall complete max_iterations number of iterations.

The program shall not accept user input aside from the arguments sent in to it.

For the first iteration, each cell shall have a _percent_ percentage chance of being alive.

The only two states a cell may be in are alive or dead.
