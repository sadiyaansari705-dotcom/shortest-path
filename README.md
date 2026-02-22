Dijkstra’s Algorithm in C (Shortest Path)

This project implements Dijkstra’s Shortest Path Algorithm in C using:

✅ Adjacency Matrix

✅ Greedy Approach

✅ Distance Array

✅ Visited Array

The program calculates the shortest distance from a source vertex to all other vertices in a weighted graph.

🧾 Program Description

The program:

Represents a graph using a 5 × 5 adjacency matrix

Uses INF = 9999 to represent infinity

Finds the vertex with minimum distance using minDistance()

Updates shortest distances using Dijkstra’s algorithm

Prints the final shortest distances from the source vertex

🧠 Concepts Used

Graph Data Structure

Weighted Graph

Adjacency Matrix

Greedy Algorithm

Shortest Path Algorithm

Arrays

🔄 How Dijkstra’s Algorithm Works

Initialize all distances as infinite (INF).

Set the source distance to 0.

Pick the vertex with the minimum distance that is not yet visited.

Update distances of its adjacent vertices.

Repeat until all vertices are visited.

📊 Graph Representation (Adjacency Matrix)
     0   1   2   3    4
0  [ 0  10   0  30  100 ]
1  [10   0  50   0    0  ]
2  [ 0  50   0  20   10  ]
3  [30   0  20   0   60  ]
4  [100  0  10  60    0  ]

This is a weighted graph where values represent edge weights.

📤 Sample Output
Vertex    Distance from Source
0          0
1          10
2          50
3          30
4          60
🚀 How to Run
🔹 Compile the Program
gcc main.c -o dijkstra
🔹 Run the Program
./dijkstra

(For Windows)

dijkstra.exe
📂 Project Structure
📁 dijkstra-shortest-path
 ├── main.c
 └── README.md
⚠️ Limitations

Number of vertices is fixed (#define V 5)

Uses adjacency matrix (not efficient for very large graphs)

Does not handle negative edge weights

Does not print actual shortest path, only distances

🔧 Possible Improvements

Make number of vertices dynamic

Take graph input from user

Print actual shortest paths

Use adjacency list for better efficiency

Implement using priority queue (min-heap)

👨‍💻 Author


B.Tech Student

If you want, I can also provide:

⭐ Version with path printing

⭐ Priority Queue (Min Heap) version

⭐ Lab viva explanation notes

⭐ Comparison between BFS, DFS, and Dijkstra
