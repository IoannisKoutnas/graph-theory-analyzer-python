# Graph Theory Visualizer & Analyzer — Python

## Overview

This project is an interactive Python application for exploring and understanding fundamental graph algorithms through visualization and controlled animation.  
It applies classical graph theory techniques to a real-world network structure and presents results in a clear, interpretable way.

The application uses the **Zachary Karate Club** graph and provides step-by-step insight into traversal order, connectivity, and structural properties of the network.

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

### 1. Install required libraries

```bash
pip install networkx matplotlib
