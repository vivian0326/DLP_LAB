# LAB 2 Description

## Explanation of N-tuple Network
In 2048, we have a 4x4 grid, 16 cells,  which is defined as board in our code. An n-tuple network, defined as pattern in our code, 
consists of n-tuples that covers n cells. If we construct a pattern as {0, 1, 2, 3, 4, 5}, it is a 6-tuple network which is shown below.  

<img src="https://user-images.githubusercontent.com/57569257/125382997-445fe900-e3c9-11eb-92b3-b898c36e2afd.png" height="200">  

Each pattern has at most 8 type of isomorphic, i.e., 4 type of rotation (0°/90°/180°/270°) and 4 type of reflection and rotation. For example,  

<img src="https://user-images.githubusercontent.com/57569257/125383317-d1a33d80-e3c9-11eb-9d62-945d2f97b2e0.png" height="200">  

We evaluate the value of the given board state by summing up all the weights of the isomorphic n-tuple which are obtained by looking up a weight table, defined as feaure in our code.  
  
We choos the following 4 n-tuple network,  
{1, 5, 6}      , {0, 1, 2, 5}  
{0, 1, 2, 5, 9}, {4, 5, 8, 9, 10}  
<img src="https://user-images.githubusercontent.com/57569257/125384356-63f81100-e3cb-11eb-9f31-af40b48d1eb8.png" width="400">  
<img src="https://user-images.githubusercontent.com/57569257/125384394-72462d00-e3cb-11eb-976a-9b65b8901153.png" width="405">
