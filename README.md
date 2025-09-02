#Martian Trail
This is a pathfinding visualization project that simulates a Mars rover navigating a grid to find the shortest, safest path to a destination.

How to Run
1) Open the index.html file in your web browser.
2) Click on a cell to set the start and end points.
3) Click or drag on other cells to add obstacles.
4) Click "Find Path" to see the rover calculate and follow the optimal route.

#Core Concepts Used: This project was built to demonstrate a fundamental data structures and algorithms (DSA) concept.
a) Graphs: The grid is modeled as a graph, where each cell is a node and the connections between them are the possible paths.
b) The A* Algorithm: This is the core pathfinding algorithm used. It efficiently finds the shortest path by using a combination of the actual distance traveled and an estimate of the distance to the destination.

#Key Data Structures:
2D Array: The entire grid and all its cells are stored in a two-dimensional array for easy organization.
Set: A Set data structure is used to keep track of the nodes that have already been visited, preventing the algorithm from getting stuck.

#Web Technologies: 
The user interface and all the interactive logic are built using HTML, CSS, and JavaScript.
