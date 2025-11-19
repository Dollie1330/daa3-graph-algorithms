# Lab Assignment 3 — Graph Algorithms in Real-World Applications
**Course:** Design and Analysis of Algorithms (ENCA351)  
**Faculty:** Dr. Aarti Sangwan  
**Student:** dollie 
**Session:** 2025-26

## Project Overview
This assignment implements four real-world problems mapped to graph algorithms:
1. Social network friend suggestion — BFS/DFS  
2. Route finding with possible negative edges — Bellman-Ford  
3. Emergency response / fastest route — Dijkstra (min-heap)  
4. Network cable installation — Minimum Spanning Tree (Kruskal + Prim)

All code is implemented in Python and is Colab-ready. Timing and memory profiling (using `time` and `tracemalloc`) are included. Plots show time vs. input size for each algorithm.

## Files to submit
- `graph_realworld.ipynb` — Colab notebook (code & experiments)  
- `README.md` — this file  
- `requirements.txt` — Python dependencies (optional)  
- `images/` — saved plots (optional)

## How to run (Google Colab)
1. Open https://colab.research.google.com  
2. Upload `graph_realworld.ipynb` or copy & paste the notebook cells.  
3. Run all cells sequentially. Plots are saved to `/images`.

## Experiment notes
- Problem1: Suggest friends of friends by counting mutual friends (BFS). Complexity O(V+E).
- Problem2: Bellman-Ford finds shortest paths with negative edges and detects negative cycles. Complexity O(V*E).
- Problem3: Dijkstra uses a min-heap (priority queue). Complexity O(E log V).
- Problem4: Kruskal (Union-Find) and Prim implemented; compare runtimes. Complexity O(E log V).

## Dependencies
