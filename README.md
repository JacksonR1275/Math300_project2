# Math300_project2
This project compares two methods for finding the shortest paths of weighted graphs on nodes. 
We built the random graph generator to produce a random 10-vertex graph, with weigthed edges, however the numbers of vertices and range of edge-weight can be adjusted in the code. 
With the random graph, you can implement Djikstra's algorithm which is the first method of finding the shortest path. 
This method will explore the unvisited node with the connected edge with the lowest weight, assigning all unattainabile nodes a value of infinity. 
The new algorithm on the other hand, groups the vertices based on their distances and solves the problem recursively. 
This algorithm utilizes edge relaxation to constantly check for shorter routes from one vertex to another. 
Each file builds on each other. 
Dijkstra uses the Random Graph Generator and Project implements both algorithms in the same file along with the random graph generator to show a direct comparison between the two.

**********AI Use Statement**********
AI was only used for debugging and testing our code. Copilot was not used to generate code. 
