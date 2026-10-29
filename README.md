# 🗺️ Dijkstra's Shortest Path Algorithm in Python

An implementation of **Dijkstra's Shortest Path Algorithm** built from scratch in Python as part of the **freeCodeCamp Scientific Computing with Python** certification curriculum.

## 🚀 About the Project
This program calculates the shortest path and minimum distance from a starting node to all other nodes in a weighted graph. It demonstrates core computer science and data structure concepts such as greedy algorithms, adjacency lists, tuple unpacking, and dictionary manipulation.

## 🛠️ Features
* **Graph Representation:** Uses an adjacency list to map nodes and edge weights.
* **Greedy Path Selection:** Dynamically picks unvisited nodes with the smallest known distance using Python's `min()` with key mapping.
* **Distance Relaxation:** Iteratively checks and updates paths when a shorter route is discovered.
* **Path Reconstruction:** Accurately tracks and prevents reference mutations using list slicing.
* **Ternary Output Conditional:** Cleanly formats output based on user target selection.

## 💻 Code Structure
The main function `shortest_path(graph, start, target)` performs the following steps:
1. Initializes distance tracking (setting start to `0` and all other nodes to `float('inf')`).
2. Iterates through unvisited nodes to find optimal routes.
3. Evaluates neighbor edge weights against recorded distances.
4. Returns or prints the final shortest distances and paths.

