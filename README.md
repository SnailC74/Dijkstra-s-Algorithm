# Dijkstra-s-Algorithm

Hongyu Chen

200362471

CS 340 - 70

Assignment 4 Part II

The steps use Dijkstra’s algorithm to find the shortest path in a grph:

1.Create a set sptSet (shortest path tree set), which tracks the vertices contained in the shortest path tree, that is, the vertices that calculate and determine the minimum distance from the source. Initially, this set is empty.

2.Assign a distance value to all the initial input diagrams. Initialize all distance values to INFINITE. The distance value from the top of the source is designated as 0, and the brake selects it first.

3.While sptSet doesn’t include all vertices

a. Pick a vertex u which is not there in sptSet and has minimum distance value.

b. Include u to sptSet.

c. Update the distance values of all adjacent vertices of u. To update the distance value, traverse all adjacent end points. For each adjacent vertex v, if the sum of the distance value of u (from the source) and the weight of the edge uv is less than the distance value of v, the distance value of v is updated.
