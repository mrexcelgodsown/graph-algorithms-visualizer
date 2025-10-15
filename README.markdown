# Graph Algorithms Visualizer

A world-class, interactive web application to visualize graph algorithms including Breadth-First Search (BFS), Depth-First Search (DFS), and Dijkstra's Shortest Path. Built with vis.js for dynamic graph rendering and Tailwind CSS for a sleek, responsive design.

## Features
- **Interactive Graph Editor**: Add nodes and weighted edges dynamically.
- **Algorithm Visualization**: Step-by-step animations for BFS, DFS, and Dijkstra’s.
- **Responsive Design**: Modern UI with dark/light theme toggle, smooth gradients, and hover effects.
- **Real-Time Feedback**: Info panel displays algorithm progress and results (e.g., shortest path distance).
- **Clean Code**: Modular JavaScript with clear documentation.

## Demo
Try it live at [https://your-username.github.io/graph-algorithms-visualizer](https://your-username.github.io/graph-algorithms-visualizer).

![Demo GIF](assets/demo.gif)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/graph-algorithms-visualizer.git
   ```
2. Open `index.html` in a modern browser (no server required).

## Usage
1. Enter node IDs (e.g., A, B) and weights to add edges.
2. Select an algorithm (BFS, DFS, or Dijkstra’s).
3. Specify start (and end for Dijkstra’s) nodes, then click "Run Algorithm".
4. Toggle themes or clear the graph as needed.

## Tech Stack
- **Frontend**: HTML, JavaScript, vis.js (graph visualization)
- **Styling**: Tailwind CSS (responsive, modern design)
- **Fonts**: Inter (via Tailwind)

## Algorithm Complexities
- BFS: O(V + E) for traversal
- DFS: O(V + E) for traversal
- Dijkstra’s: O((V + E) log V) with a priority queue

## Future Enhancements
- Add more algorithms (e.g., A*, Prim’s).
- Implement undo/redo for graph edits.
- Add export/import for graph configurations.

## License
MIT License