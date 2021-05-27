# Visual Instance of Conway's Game of Life

> Rules of the Game

1. Any live cell with fewer than two live neighbours dies, as if by under population.
2. Any live cell with two or three live neighbours lives on the next generation.
3. Any live cell with more than three live neighbours dies, as if by overpopulation.
4. Any dead cell with exactly three live neighbours become a live cell as if by reproduction.

> How to play the game

1. Clone the repository

`` git clone https://github.com/Rushali-Sarkar/ConwaysGameofLife.git ``

2. Run the gameoflife.py file

`` python3 gameoflife.py ``

#### Note: Your machine should have pygame installed in it. If you donot havepygame in your system then run the command ``pip3 install pygame`` to install it.

> Change the Grid of the Game

If you want to change the grid of the game, you can edit the code the file.

1. If you want to change dimensions for a randomly made grid with live and dead cells then edit the arguments in line 245.

`` grid = make_random_grid(rows, columns) ``

In the above line by default I have added 20 rows and 20 columns.
However, you can change the dimensions of the rows and columns according to your pleasure.

2. If you want to see some famous shapes of Game of Life, there are few predefined shapes already available. They are defined as constansts: 

``i) TOAD ``

``ii) BEACON ``

``iii) BLINKER ``

``iv) GLIDER``

``v) SPACESHIP``

``vi) PENTADECATHLON``

To view the instance for these shapes you have to edit line 246.

`` gameoflife(grid) ``

In this line you can add the constant name of the predefined grid you wish to see from the list I mentioned above. 

Happy Playing !
