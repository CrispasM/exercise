# Malawi District Graph Visualization

This project visualizes the interconnectivity of Malawi's 28 districts using a force-directed graph layout algorithm (Fruchterman-Reingold via D3.js).

## Contents

- `data.js`: District nodes with initial positions + adjacency list.
- `layout.js`: Force simulation using D3.js to optimize layout.
- `index.html`: Renders the graph using SVG + D3.
- `screenshots/`: Graph layout screenshot or console output.

## Instructions

1. Clone the repository.
2. Run a local server (e.g., VS Code Live Server).
3. Open `index.html` to view the graph.
4. Check the browser console for optimized node positions.

## Dependencies

- [D3.js v7](https://d3js.org)

## Screenshot

![Graph Layout](screenshots/graph.png)
