# Metro_App
Graph Representation:

Vertices: Represented by the Vertex class. Each vertex contains a HashMap of neighboring vertices (nbrs) with the corresponding weights (distance or time).
Edges: Represented by adding entries to the HashMap of vertices. Each edge connects two vertices and has an associated weight.
Graph Operations:

Add Vertex: Creates a new vertex and adds it to the graph.
Remove Vertex: Removes a vertex and its associated edges from the graph.
Add Edge: Adds an edge between two vertices with a specified weight.
Remove Edge: Removes an edge between two vertices.
Graph Traversal:

Depth-First Search (DFS): Used in hasPath to check if a path exists between two vertices. It recursively explores all neighboring vertices.
Shortest Path Algorithms:

Dijkstra’s Algorithm: Implemented in the dijkstra method. This algorithm finds the shortest path from a source vertex to a destination vertex based on distance or time. It uses a priority queue (heap) to efficiently fetch the vertex with the minimum distance.
Min-Heap: Implemented using the Heap class. This data structure supports operations to add elements and update priorities efficiently, which is crucial for Dijkstra’s algorithm.
User Interface:

Command-Line Interface: Allows users to interact with the program via the console. Users can list stations, display the metro map, and find shortest paths between stations.
Utility Methods:

Display Functions: display_Map and display_Stations provide a way to visually inspect the graph’s structure and list of stations.
Path Extraction: Methods like Get_Minimum_Distance and Get_Minimum_Time return the shortest path along with details such as interchanges and total distance or time.
