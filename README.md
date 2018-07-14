# Game-of-life

Transition occurs when:
-Any live cell with fewer than two live neighbours dies, as if caused by underpopulation.
-Any live cell with two or three live neighbours lives on to the next generation.
-Any live cell with more than three live neighbours dies, as if by overpopulation.
-Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.

Wrap-around for the edges was used. (Ex. (-1 + 10) % 10 = 9)

Run the index file to see the output.
