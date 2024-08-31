## A* Path Finding Algorithm
This project implements the A* (A-star) pathfinding algorithm using Pygame. The A* algorithm is a popular pathfinding and graph traversal algorithm that finds the shortest path between nodes in a grid while considering obstacles.

## Features
Visual Representation: The grid is visualized using Pygame, where nodes can be marked as start, end, barriers, or traversed.
Interactive Grid: Users can set start and end nodes, place barriers, and visualize the pathfinding process.
Pathfinding Algorithm: Implements the A* algorithm to find the shortest path from the start node to the end node while avoiding barriers.

## Installation
To run this project, you need Python and Pygame installed. Follow these steps to set up your environment:

1 Clone the Repository

git clone https://github.com/srishty007/Path-Finding-Visualizer.git
cd Path-Finding-Visualizer

2 Install Pygame

If you don't have Pygame installed, you can install it using pip:

pip install pygame

3 Run the Application

Execute the following command to start the application:

python aster.py

## Usage
1 Setting Start and End Nodes

Left-Click: Click on a cell to set it as the start node (orange) if no start node is currently set. If a start node is already set, clicking will set the clicked cell as the end node (turquoise), if no end node is currently set.
2 Placing Barriers

Left-Click: Click on a cell to place a barrier (black) to block the path.
3 Removing Nodes and Barriers

Right-Click: Click on a cell to remove barriers or reset the start/end nodes if clicked cells are the current start or end nodes.
Running the Algorithm

Spacebar: Press the spacebar to start the A* algorithm and find the shortest path from the start node to the end node while navigating around barriers.
Clearing the Grid

C Key: Press the "C" key to clear the grid, resetting the start and end nodes, and removing barriers.

## Code Overview
Node Class: Represents a cell in the grid with attributes and methods for visualization, neighbor updating, and state management.

h(p1, p2): Heuristic function used in the A* algorithm to estimate the distance between two nodes.

reconstruct_path(came_from, current, draw): Reconstructs the path from the end node to the start node once the path is found.

algorithm(draw, grid, start, end): Implements the A* pathfinding algorithm to find and visualize the shortest path.

make_grid(rows, width): Creates a grid of nodes.

draw_grid(win, rows, width): Draws grid lines on the Pygame window.

draw(win, grid, rows, width): Updates the Pygame window with the current state of the grid.

get_clicked_pos(pos, rows, width): Converts mouse click positions to grid cell coordinates.

main(win, width): Main function to run the Pygame loop, handle events, and manage user interactions.

## Contributing
Feel free to contribute to this project by submitting issues or pull requests. Contributions and feedback are welcome!

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any questions or feedback, please contact:

Author: [Srishty007]
Email: [ranjansrishty49@gmail.com]
