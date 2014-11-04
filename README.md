passage
=======

A proof of concept code for finding path in a 3D terrain.

The idea is basically to convert the point data to graph with edges connecting each point with its nearest neighbours and then to use [Bellman-Ford](https://en.wikipedia.org/wiki/Bellman-Ford_algorithm) to find the shortest path.
