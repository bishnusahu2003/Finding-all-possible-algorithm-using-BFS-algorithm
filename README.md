# Finding-all-possible-path-algorithm-using-BFS-algorithm
INTRODUCTION

The search for all possible paths in a graph is a fundamental problem in computer science and is applicable to various domains, such as network routing, maze solving, and path planning. One popular algorithm for tackling this problem is the Breadth-First Search (BFS) algorithm. BFS is a graph traversal technique that systematically explores all the vertices of a graph, starting from a given source vertex, in a breadth ward motion.
In this article, we will delve into the concept of finding all possible paths using the BFS algorithm. We will explore how BFS can be used to systematically traverse a graph, identify different paths, and store them efficiently. By the end, you will have a clear understanding of the BFS algorithm's application for path-finding tasks.
OVERVIEW : We will begin by providing a brief overview of the BFS algorithm, explaining its key features for finding all possible path form source to destination, and discussing its primary advantages and limitations. This section will serve as a refresher for those familiar with BFS and a primer for those encountering it for the first time.
PROBLEM DESCRIPTION (BFS Algorithm for Path-Finding) : This section will focus on adapting the BFS algorithm specifically for finding all possible paths in a graph. We will discuss the modifications required to transform the traditional BFS into a path-finding BFS. This will include techniques for tracking and storing the discovered paths efficiently.
We can find all possible path from source to destination using Breadth First Search. According to the BFS, you must traverse the graph in a breadthwise direction:
Breadth-First Search uses a queue data structure to store the node and mark it as "visited" until it marks all the neighbouring vertices directly related to it. The queue operates on the First In First Out (FIFO) principle, so the node's neighbours will be viewed in the order in which it inserts them in the node, starting with the node that was inserted first.
 
How Does the BFS Algorithm Work?

Breadth-First Search uses a queue data structure technique to store the vertices. And the queue follows the First In First Out (FIFO) principle, which means that the neighbours of the node will be displayed, beginning with the node that was put first.


The transverse of the BFS algorithm is approaching the nodes in two ways.
●	Visited node
●	Not visited node

How Does the Algorithm Operate?

●	Start with the source node.
●	Add that node at the front of the queue to the visited list.
●	Make a list of the nodes as visited that are close to that vertex.
●	And dequeue the nodes once they are visited.
●	Repeat the actions until the queue is empty
●	The Architecture of the BFS Algorithm
