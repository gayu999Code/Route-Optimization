# Route-Optimization
This repository implements Dijkstra's and A algorithms* for route optimization, with visualization using the Pygame library. The project allows users to interactively explore the shortest path between two points on a grid.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies](#technologies)
- [Setup](#setup)
- [Usage](#usage)
- [Algorithm Details](#algorithm-details)
- [Contributing](#contributing)
- [License](#license)

## Overview
Route optimization is essential in many applications like GPS navigation, logistics, and AI for games. This project visualizes how **Dijkstra's** and **A*** algorithms can be used to find the shortest path between two points on a grid, taking into account various obstacles and terrain types.

## Features
- **Dijkstra's Algorithm**: Guarantees the shortest path, works for all edge weights.
- **A* Algorithm**: More efficient with heuristics (such as Manhattan Distance), designed for grid-based pathfinding.
- **Grid Visualization**: See how each algorithm explores the grid, one node at a time.
- **Interactive Interface**: Users can create obstacles, set start and end points, and visualize the pathfinding process.
- **Comparison Mode**: Compare how Dijkstra and A* perform on the same problem.

## Technologies
- **Python 3.x**
- **Pygame Library**

## Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/route-optimization.git
   cd route-optimization
   ```

2. **Install Dependencies:**
   You need to have Python installed. To install the required libraries, run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Project:**
   ```bash
   python dijistra.py
   ```
    ```bash
   python AStar.py
    ```
## Usage

1. **Grid Setup:**
   - Left-click to place the start point.
   - Right-click to place the end point.
   - Drag to place obstacles on the grid.

2. **Start the Visualization:**
   - Press `D` for Dijkstra's Algorithm.
   - Press `A` for A* Algorithm.

3. **Reset Grid:**
   - Press `R` to reset the grid and start over.

## Algorithm Details

- **Dijkstra's Algorithm**: Explores every possible path uniformly, making it slower but guaranteed to find the shortest path even with varying edge costs.
- **A * Algorithm**: Uses a heuristic (such as the Manhattan Distance or Euclidean Distance) to guide the search, which makes it faster in practice for many grid-based problems.


## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

