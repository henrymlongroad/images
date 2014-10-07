#COMP3 Trees Homework

##Question 1

![](https://www.dropbox.com/s/opzliuml1pgjktf/question_one.jpg?dl=1)

Using the graph above, answer the following questions:

1. How many edges are there in the graph? (**1 mark**)
the graph has 6 unlabeled edges
2. How many vertices are there in the graph? (**1 mark**)
 the graph has 5 vertices 
3. What is the degree of vertex A? (**1 mark**)
 
4. What is the degree of vertex C? (**1 mark**)
5. What are the neighbours of vertex E? (**1 mark**)
 the neighbours of vertex E are C , D
6. Represent this graph as an adjacency matrix (**1 mark**)
|vertex|A|B|C|D|E|
|:-:|:-:|:-:|:-:|:-:|
|A|-|1|1|-|-|
|B|1|-|1|-|-|
|C|1|1|-|1|1|
|D|-|-|1|-|1|
|E|-|-|1|1|-|

7. Represent this graph as an adjacency list (**1 mark**)
|vertex|adjacent vertex|
|:-:|:-:|:-:|:-:|:-:|
|A|B,C|
|B|A,C|
|C|A,B,D,E|
|D|C,E|
|E|C,E|
8. Why is this graph not a tree? (**1 mark**)
a tree has a root node that extends down to other nodes and all other nodes have only two extensions of themselves
9. Given a starting point of C can you find a solution to the explorer’s problem for this graph?  If so what is your solution? (**2 marks**)
10. Given a starting point of C can you find a solution to the traveller’s problem for this graph?  If so what is your solution? (**2 marks**)
 

**Total 12 marks**

##Question 2
Draw the graph represented by this adjacency list.

|Vertex|Adjacent vertices|
|:----:|-----------------|
|A|B,C,E|
|B|A,D|
|C|A,D|
|D|B,E,C|
|E|A,D|

![adjacentcy list graph](https://raw.githubusercontent.com/henrymlongroad/images/master/List%20graph.png)
(**Total 5 marks**)

##Question 3
Draw the graph represented by this adjacency matrix:

|Vertex|A|B|C|D|E|
|:----:|-|-|-|-|-|
|**A**|0|1|1|0|0|
|**B**|0|0|0|0|0|
|**C**|1|1|0|1|1|
|**D**|1|0|0|0|0|
|**E**|0|1|0|1|0|

![](https://raw.githubusercontent.com/henrymlongroad/images/master/Untitled.png)
(**Total 5 marks**)

##Question 4
Describe the **advantages** and **disadvantages** of an adjacency matrix compared with an adjacency list.

(**Total 2 marks**)

##Question 5
Provide definitions for the following terms:

1. Graph (**1 mark**)
2. Tree (**1 mark**)
3. Path (**1 mark**)
4. Cycle (**1 mark**)
5. Circuit (**1 mark**)

**Total 5 marks**

**Overall Total 29 marks**


