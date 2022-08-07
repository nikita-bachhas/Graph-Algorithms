# Graph Algorithms
Implemented Breadth First Search (BFS) algorithm when traversing through tree or graph data structures when searching for the nearest hospital in a locality map

## Problem Statement 
In a given number of nodes (i.e. the locality map), traverse the neighbouring nodes to find the nearest hospital nodes from a starting node 

## Functionality
1. Implemented the BFS algorithm to find the nearest hospital node by controlling the following variables: Total number of nodes (n), Number of hospitals (h), Number of hospitals to be searched (k)
2. BFS search is carried out level-by-level (i.e. by searching through all adjacent nodes first before proceeding to the next level)

## Conclusion
1. When n is small, the time taken is relatively the same but increases rapidly when k is higher (e.g. finding the two nearest hospitals or more). This supports the theoretical worst-case time complexity of O(kh+km) 
2. Initial increase of h results in a significant decrease in the time taken, but little to none when h becomes too big
3. Time take increases exponential as k increases as we have to find more and more closest hospital nodes to the starting node 

## Documentation
1. Full detailed report of the project: [CZ2001 Project 2.pdf](https://github.com/nikita-bachhas/Graph-Algorithms/blob/main/CZ2001%20Project%202.pdf)
2. Summary and presentation of the project: [CZ2001 Project 2.pptx](https://github.com/nikita-bachhas/Graph-Algorithms/blob/main/CZ2001%20Project%202.pptx)

## Developed by:
1. Ang Shu Hui
2. Bachhas Nikita
3. Kundu Koushani
4. Leonardo Irvin Pratama
