# Graph Theory Visualization Tool 🕸️

![License](https://img.shields.io/badge/License-MIT-blue.svg) ![React](https://img.shields.io/badge/React-18.2-blue) ![Status](https://img.shields.io/badge/Status-Deployed-success)

**[🔴 VIEW LIVE DEMO HERE](PASTE_YOUR_VERCEL_LINK_HERE)**

## 📖 Overview
The **Graph Theory Visualization Tool** is an interactive web application designed to demonstrate the efficiency and logic of fundamental graph traversal algorithms. It helps users visualize how algorithms like **Dijkstra** and **A*** navigate nodes and edges to discover shortest paths in a weighted, dynamic grid environment.

This project focuses on the intersection of **Algorithm Design** and **Frontend Performance**, rendering complex logic in real-time at 60fps.

## 🚀 Features
* **Pathfinding Algorithms:** Visualizes Dijkstra, A* (A-Star), Breadth-First Search (BFS), and Depth-First Search (DFS).
* **Maze Generation:** Includes Recursive Division logic to automatically generate complex mazes.
* **Interactive Grid:** Users can draw "Walls" (removing edges) and move Start/End nodes to test edge cases.
* **Real-Time Animation:** Visualizes the "visited" nodes set and the final "shortest path" backtracking process.

## 🧮 Algorithms Implemented
1.  **Dijkstra's Algorithm:** The father of pathfinding algorithms; guarantees the shortest path using a weighted graph.
2.  **A* Search:** Uses heuristics to guarantee the shortest path much faster than Dijkstra.
3.  **Breath-First Search (BFS):** Great for unweighted graphs; guarantees the shortest path.
4.  **Depth-First Search (DFS):** A bad algorithm for pathfinding (does not guarantee shortest path), included for educational comparison.

## 🛠️ Tech Stack
* **Frontend Library:** React.js
* **Styling:** CSS3 (Animations & Keyframes)
* **Data Structures:** 2D Arrays, Queues, Stacks
* **Deployment:** Vercel

## ⚙️ How to Run Locally

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/VanshKardam/Graph-Theory-Tool.git](https://github.com/VanshKardam/Graph-Theory-Tool.git)
    cd Graph-Theory-Tool
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Run the application**
    ```bash
    npm start
    ```
    Open [http://localhost:1337](http://localhost:1337) to view it in the browser.

## 🧠 Engineering Challenges
* **State Management:** Optimized React state to handle grid updates without triggering full-page re-renders, ensuring smooth performance on large grids.
* **Asynchronous Animation:** Decoupled the algorithm's calculation speed from the visualization speed using JavaScript timers to create a fluid user experience.

---
*Developed by Vansh*
