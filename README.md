# Pathfinding Simulator implementing Dijkstra and A* algorithms
1.A pathfinding simulator using SFML(Simple and Fast Multimedia Library) for comparing optimality and speed of Dijkstra and A* algorithms.
# Video Analysis
![This is an image](https://raw.githubusercontent.com/UditSinghParihar/Pathfinding_Simulator/master/astar_vs_dijkstra.jpg)
# 1. Stimulation video
# Implementation
# #1.Color coding :
  1. Open cells - White
  2. Blocked cells - Black
  3. Start and End cells - Blue and Red
  4. Explored cells - Yellow
  5. Shortest Path of Dijkstra and A-star - Green and Magenta
# #2.Major components :
   1.Main loop to render frames at 60 frames/second
   2.Dijkstra program
   3.Astar program
# #3.Implementation.
   1.Map as 2D array of cells
   2.Binary representation of cells as 0 and 1 for blocked and open cells
   3.Each cell has information of its parent and its state of exploration
# #4.Heuristics for a node having coordinates (node_x, node_y) is : 
   1.Horizontal and vertical cost: D1 = 1
   2.Diagonal cost: D2 = √2
   3.Abscissa difference: dx = |goal_x – node_x|
   4.Ordinate difference: dy = |goal_y – node_y|
   5.Diagonal heuristics: h = D1* |dx - dy| + D2* min(dx, dy)
# Build
  1. If you are using non-Linux OS, then see how to build SFML and compile programs for your Operating System [Link](https://www.sfml-dev.org/tutorials/2.5/#getting-started)

