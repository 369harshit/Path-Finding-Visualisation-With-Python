# Path-Finding-Visualisation-With-Python
DSA Project

Path-Finding-Visualisation-with-Pygame
A path-finding visualisation program using Pygame

Features 

1. Pygame GUI
2. Placeable walls/obsticles in the gui
3. Placeable checkpoints for the pathfinding algorithm to follow
4. 4 different pathfind algorithms; Depth-first search, Breadth-first search, dijkstra and A*
5. Hotkeys to remove cirtain details from the gui
6. Adjustable speed of visualisation
7. Adjustable size of the grid by scrolling
   
Keybinds listed at the bottom of the readme



Depth-first Search
1. Rule of expansion - Expand most recently added node
2. Order of expansion - Up, Right, Down, Left
3. Doesn't give the shortest route most of the time
4. Acts like humans in perfect mazes and sometimes can be way faster than other algorithms

   
![DFS-Empty-ezgif com-crop (1)](https://github.com/user-attachments/assets/323b468b-4f96-4bd2-a3aa-87c4b4b1bbf4)         

![DFS-1-ezgif com-crop](https://github.com/user-attachments/assets/53e97093-3cae-40cc-b298-f229a72a726f)

![DFS-2-ezgif com-crop](https://github.com/user-attachments/assets/48a9796f-c52b-490a-9397-946f4728ff89)

5. However even on the simplest mazes it can skip right past the end point
 
![DFS-3-ezgif com-crop](https://github.com/user-attachments/assets/fc5d4bb6-f38f-4613-8644-7f886ab070f8)



Breadth-first search
1. Rule of expansion - Expand least recently added node
2. Acts like a wide net that covers every node that is closest in order
3. Always finds optimal route, however can be quite slow in long range searches
   
![BFS-2-ezgif com-crop](https://github.com/user-attachments/assets/e368284a-9d1e-49e7-b76e-805378ae7d0e)

![BFS-1-ezgif com-crop](https://github.com/user-attachments/assets/14153a15-3d16-464c-a582-133eb08bbeba)

![BFS-Empty-ezgif com-crop](https://github.com/user-attachments/assets/16761c5a-12d0-4f51-b38b-f9cd0baec8f2)



Dijkstra
1. Rule of expansion - Expand node closest to starting node using g value
2. Because in this visualisation it can only move in 4 directions BFS and Dijkstra are identical in result but Dijkstra uses more computational power

![Dijkstra-Empty-ezgif com-crop](https://github.com/user-attachments/assets/6e4b007f-e4c6-4354-a537-1d8ef367100c)

![Dijkstra-2-ezgif com-crop](https://github.com/user-attachments/assets/aa955a22-2185-4f47-b37d-4b78fb97b1e6)

![Dijkstra-1-ezgif com-crop](https://github.com/user-attachments/assets/cf715e80-4e1e-46fd-b499-e4a43dc3343f)



A Star
1. Rule of exspansion - Expand node with lowest f value, aka node that is close to the straightest diagonal path from the start node to end node put simply
2. Hueristic used is Manhanntan Distance

![AStar-Empty-ezgif com-crop](https://github.com/user-attachments/assets/e73bf734-b029-43b9-8279-3d11912dec36)

![AStar-2-ezgif com-crop](https://github.com/user-attachments/assets/cc1c2a50-df14-4198-825e-212edfc7b5c7)

![AStar-1-ezgif com-crop](https://github.com/user-attachments/assets/ac635352-cc7c-4e3e-99b0-50e45ad92f6e)


Keybinds
1.  1-9: Place checkpoints for the pathfinding algorithm
2.  Left Mouse Click: Place walls
3.  Right Mouse CLick: Remove walls or checkpoints
4.  q: Run DFS algorithm
5.  w: Run BFS algorithm
6.  e: Run Dijkstra algorithm
7.  r: Run A Star algorithm
8.  z: Remove the last runs visualisation
9.  x: Completely clear the board
10. Mouse Scroll: Zoom in and out
11. Space: Generate random walls/maze
12. +: Increase speed of animation
13. -: Decrease speed of animation



   










