## Cuthill-Mckee Algorithm:



The goal of the Cuthill-Mckee (and reverse Cuthill-Mckee) ordering algorithm is to reduce the [bandwidth](https://www.boost.org/doc/libs/1_75_0/libs/graph/doc/bandwidth.html) of a graph by reordering the indices assigned to each vertex. The Cuthill-Mckee ordering algorithm works by a local minimization of the i-th bandwidths. The vertices are basically assigned a breadth-first search order, except that at each step, the adjacent vertices are placed in the queue in order of increasing degree.

Below is an animation for visualisation of Cuthill-Mckee (and reverse Cuthill-Mckee) ordering algorithm.

In the below gif following color represents different states of node:
```
    grey - unvisited
    yellow - being visited
    green - visited
```


![download (1)](https://user-images.githubusercontent.com/32921778/112771147-1a67fe00-9048-11eb-9d48-5384e699358a.gif)


