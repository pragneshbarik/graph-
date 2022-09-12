# **graph++**


Minimal C++ libary for performing graph operations.



## **Algorithms**



### 1. Basic Paths and Cycles

```
    addDirectedEdge(start, end, weight)
    addUndirectedEdge(start, end, weight)
    getDegree(vertex)
    hasPath(src, dest)
    allPaths(src, dest)
    connectedVertices(vertex)
    splitConnectedComponents()
    isConnected()
    isEulerian()
    explore(vertex)
```

### 2. Hamiltonian
```
    hamiltonian.paths(src)
    hamiltonian.cycles(src)
```

### 3. Minimal Spanning Trees

```
    * mst.prim()
    * mst.krushkal()
```

### 4. Single Source Shortest Paths

```
    singleSourceShortestPaths.dijkstra(src)
    singleSourceShortestPaths.aStar(src)
```

### 5. Advanced 
```
    * topologicalSort()
```


> methods marked * are still in development.