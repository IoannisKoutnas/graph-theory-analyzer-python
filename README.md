# Graph Theory Analysis – Karate Club

An interactive Python application that visualizes and analyzes the classic Karate Club graph using graph theory algorithms.

## Features
- Breadth-First Search (BFS) traversal animation
- Depth-First Search (DFS) traversal animation
- Greedy graph coloring visualization
- Cycle detection
- Maximum clique finding and visualization
- Logging panel for outputs

## Tech Stack
- Python 3
- Tkinter (for GUI)
- Matplotlib (for graph drawing and animation)
- NetworkX (graph algorithms)

## Installation

1. **Clone the repository**
    ```
    [git clone (https://github.com/IoannisKoutnas/graph-theory-analyzer/)]
    cd graph-theory-analyzer
    ```

2. **(Optional but recommended) Set up a virtual environment**
    ```
    python -m venv venv
    source venv/bin/activate    # On Windows: venv\Scripts\activate
    ```

3. **Install dependencies**
    ```
    pip install -r requirements.txt
    ```

    - If Tkinter is missing, install it via your system’s package manager:
        - **Windows:** usually included with Python
        - **Ubuntu/Debian:** `sudo apt-get install python3-tk`
        - **MacOS:** included with Python or use `brew install python-tk`

4. **Run the application**
    ```
    python main.py
    ```

---

## Usage

- Choose actions like BFS, DFS, Coloring, Cycle, or Clique from the right-side control panel.
- The graph visualization and the log window will display results for each algorithm step.
- Use "Clear Log" to reset and "Exit" to close the program.
