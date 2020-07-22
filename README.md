# A-Star-Pathfinding

Implementing and visualizing the A* Pathfinding Algorithm using Pygame. The GUI takes in a start (colored Orange) and an end point (colored Turquiose) by the user, 
then user-defined barriers (colored black) to be traversed by the algorithm. Pressing the space bar will start the program's pathfinding algorithm which then 
results in the shortest path (if one is found). 

Right-clicking erases squares and anything can be redrawn once erased. Pressing the 'c' key on your keyboard will erase all squares at once. 

Concepts explored:

- Input from user (start and end points, barriers, keystrokes)
- Priority Queues & Sets
- Heuristic functions to derive pathfinding and shortest path
- Manhattan Distance
- Object Oriented Programming


## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install Pygame.

```bash
pip install pygame
```
or

```bash
pip3 install pygame
```

More on A*:

A* (pronounced "A-star") is a graph traversal and path search algorithm, which is often used in many fields of computer science due to its completeness, 
optimality, and optimal efficiency. One major practical drawback is its space complexity (O(b^d)) as it stores all generated nodes in memory. 
Thus, in practical travel-routing systems, it is generally outperformed by algorithms which can pre-process the graph to attain better performance, 
as well as memory-bounded approaches; however, A* is still the best solution in many cases
