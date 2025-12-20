````markdown
# Graph Theory Visualizer & Analyzer — Python

## Overview

This project is an interactive Python application for exploring and understanding fundamental graph algorithms through visualization and controlled animation.  
It applies classical graph theory techniques to a real-world network structure and presents results in a clear, interpretable way.

The application uses the Zachary Karate Club graph and provides step-by-step insight into traversal order, connectivity, and structural properties of the network.

---

## Objectives

- Provide a clear visual representation of graph algorithms
- Demonstrate algorithm behavior through controlled animation
- Expose structural properties of networks in an interpretable format
- Maintain clean separation between logic, visualization, and interface

---

## Features

### Traversal Algorithms
- **Breadth-First Search (BFS)**
  - Level-based exploration with depth tracking
  - Animated node progression
- **Depth-First Search (DFS)**
  - Recursive traversal with visual feedback

### Graph Structure Analysis
- **Greedy Coloring**
  - Assigns the minimum possible colors so adjacent nodes differ
- **Cycle Detection**
  - Identifies whether cyclic paths exist in the graph
- **Maximum Clique Detection**
  - Locates and highlights the largest fully connected subgroup

### Visualization & Interface
- Animated graph updates using Matplotlib
- Fixed layout for consistency and comparability
- Scrollable log panel for step-by-step output
- GUI controls for running and resetting analyses

---

## Tech Stack

- Python 3
- NetworkX
- Matplotlib
- Tkinter

---

## How to Run

1. Install required libraries:
   ```bash
   pip install networkx matplotlib
````

2. Run the application:

   ```bash
   python main.py
   ```

---

## Usage

* Select an operation (BFS, DFS, Coloring, Cycle, Clique) from the control panel
* Observe the algorithm execution directly on the graph
* Review detailed results in the log window
* Reset the interface using **Clear Log**

---

## Graph Source

* Zachary Karate Club network
  34 nodes, 78 edges

---

## Design Notes

* Algorithms are implemented explicitly for clarity and correctness
* Visual feedback is synchronized with traversal logic
* Layout is fixed to support consistent interpretation
* The application is structured for easy extension and reuse

---

## Author

Ioannis Koutnas

---

## License

MIT License


