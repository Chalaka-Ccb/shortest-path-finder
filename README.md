# 🧭 Shortest Path Finder in Python

A Python implementation of a shortest path algorithm for weighted, undirected graphs. This project calculates the minimum distance and path between nodes using a variation of Dijkstra’s algorithm.

---

## 📌 Features

- Accepts any graph as an adjacency list with edge weights
- Computes shortest path from one source to:
  - A specific target node
  - Or all other nodes
- Displays:
  - Total cost
  - Step-by-step path

---

## 🧠 How It Works

The function `shortest_path(graph, start, target='')`:
- Initializes distance and path dictionaries
- Iteratively selects the nearest unvisited node
- Updates paths and distances if shorter path found
- Outputs distance and route

---

## 📁 Example Graph Input

```python
my_graph = {
    'A': [('B', 5), ('C', 3), ('E', 11)],
    'B': [('A', 5), ('C', 1), ('F', 2)],
    'C': [('A', 3), ('B', 1), ('D', 1), ('E', 5)],
    'D': [('C',1 ), ('E', 9), ('F', 3)],
    'E': [('A', 11), ('C', 5), ('D', 9)],
    'F': [('B', 2), ('D', 3)]
}
"📁 Example Graph Input"
python shortest_path.py

👨‍💻 Author
Chalaka Chamikara
Passionate about algorithms, real-world logic, and building educational tools with Python.



