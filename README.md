# Bellman-Ford Simulation

An interactive web application for visualizing shortest-path algorithms on weighted graphs. The project demonstrates the Bellman-Ford algorithm, detects negative-weight cycles, and provides a comparison with Dijkstra's algorithm.

## Overview

Bellman-Ford Simulation is an educational project designed to help users understand how shortest-path algorithms work through interactive graph visualization and step-by-step execution.

Users can create or import a weighted graph, select source and destination vertices, run algorithms, and observe how distances are updated during each iteration.

## Features

- **Interactive Graph Visualization**
  - Display weighted directed graphs.
  - Drag and drop vertices to adjust their positions.
  - Visualize graph edges and weights.

- **Graph Configuration**
  - Add edges manually.
  - Remove edges from the graph.
  - Import graph data from `.txt` or `.csv` files.
  - Select source and destination vertices.

- **Bellman-Ford Algorithm**
  - Calculate shortest paths from a selected source vertex.
  - Display distance updates across iterations.
  - Detect negative-weight cycles.

- **Dijkstra's Algorithm**
  - Run Dijkstra's algorithm for shortest-path calculation.
  - Compare its results with Bellman-Ford.

- **Step-by-Step Results**
  - Display vertex distance tables.
  - Show detailed edge-relaxation logs.
  - Present the final shortest distance and path when available.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- SVG for graph visualization

## Project Structure

```text
Bellman-Ford-Simulation/
│
├── index.html
├── style.css
├── script.js
├── ChuTrinhAm.txt
├── ChuTrinhBinhThuong.txt
└── README.md
```

## Getting Started

### Prerequisites

- A modern web browser (Google Chrome, Microsoft Edge, Firefox, etc.).
- No backend server or database is required.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/thanhbinh-io/Bellman-Ford-Simulation.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Bellman-Ford-Simulation
   ```

3. Open `index.html` in your web browser.

You can also open the project folder in Visual Studio Code and use the Live Server extension to run it locally.

## How to Use

1. Open the application in your browser.
2. Import a graph file (`.txt` or `.csv`) or add edges manually.
3. Select the source and destination vertices.
4. Choose an algorithm:
   - **Run Bellman-Ford** to calculate shortest paths and check for negative-weight cycles.
   - **Run Dijkstra** to calculate shortest paths.
5. Observe the graph visualization, distance table, detailed execution log, and final path.

## Sample Input Files

The repository includes two sample graph files:

- `ChuTrinhAm.txt` – Sample graph containing a negative-weight cycle.
- `ChuTrinhBinhThuong.txt` – Sample graph without a negative-weight cycle.

## Learning Objectives

This project provides practical illustrations of:

- Weighted directed graphs.
- Shortest-path problems.
- Edge relaxation.
- Iterative distance updates.
- Negative-weight cycle detection.
- Differences between Bellman-Ford and Dijkstra's algorithms.

## Project Information

**Project:** Bellman-Ford Simulation  
**Course:** Fundamentals of Computer Science Practice

## Repository

[https://github.com/thanhbinh-io/Bellman-Ford-Simulation](https://github.com/thanhbinh-io/Bellman-Ford-Simulation)
