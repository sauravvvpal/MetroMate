# Project Title: Console-Based MetroApp using C++


=> Description:
The MetroMate is a C++ program designed to provide users with information about the Delhi Metro system. It allows users to input their source and destination metro stations and then displays the shortest route between the two stations, along with the corresponding fare. The program utilizes graph and heap data structures, as well as various algorithms, to achieve this functionality.

=> Functionality:

User Input: The program takes user input for the source and destination metro stations in the Delhi Metro system.

Graph Representation: The metro stations are represented as nodes in a graph. Each node contains information such as the station's name, metro corridor, and connecting lines.

Graph Edges: The connections between metro stations are represented as edges in the graph. These edges contain information about the distance between two stations, and the cost of the edge is equal to the distance between the two connecting stations.

Shortest Path Calculation: The program employs various algorithms like Dijkstra's algorithm, breadth-first search (BFS), and depth-first search (DFS) to find the shortest path between the source and destination stations.

Fare Calculation: Based on the total distance between the source and destination stations, the program calculates the fare for the metro ride.

Route Display: The program displays the metro route that the user should take to reach their destination. This route is the shortest path between the selected stations.

Metro Map: The application provides a metro map to aid commuters in navigating the metro system more effectively.

=> Implementation:
The Metro-App is implemented using C++ programming language. It utilizes the following key components and algorithms:

Graph Data Structure: The stations are represented as nodes in the graph, and the connections between stations are represented as edges.

Heap Data Structure: A heap is used to efficiently manage nodes during shortest path calculations.

Dijkstra's Algorithm: This algorithm is used to find the shortest path between two stations based on the edge distances.

Breadth-First Search (BFS): BFS is used to explore neighboring stations for pathfinding.

Depth-First Search (DFS): DFS can be utilized to traverse alternative paths in the metro network.

=> Requirements:
Dijkstras Algorithm => https://www.geeksforgeeks.org/c-program-for-dijkstras-shortest-path-algorithm-greedy-algo-7/

Depth-First Search => https://www.geeksforgeeks.org/depth-first-search-or-dfs-for-a-graph/

Breadth-First Search => https://www.geeksforgeeks.org/breadth-first-search-or-bfs-for-a-graph/
