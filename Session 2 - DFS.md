<!-- Link to Google Font -->
<link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swa" rel="stylesheet">


<span style="font-family: 'Montserrat', sans-serif;">

# Session 2 Depth First Search and A* Algorithms

## Depth First Search 
```
Depth-first search starts from a node (source) and tries to reach as deep as possible. If there is no path and all the nodes are visited, it returns to the earlier node to see if there are any other nodes that it can visit.
```
Let's see in action

https://www.hackerearth.com/practice/algorithms/graphs/depth-first-search/visualize/

![image](https://github.com/user-attachments/assets/a5d9137a-19fb-45ad-82a6-1bbc0f6162b9)

> `How does it result in solving the maze`

https://visualgo.net/en/dfsbfs

![image](https://github.com/user-attachments/assets/364cead4-fda4-4bff-8f0b-eb8325dc5a61)


## A* Algorithm

```
A* algorithm uses Heuristics calculations to find the shortest path to the destination.
This is what today's maps use to find the shortest path
```

![image](https://github.com/user-attachments/assets/4d4acdb9-74d2-4daf-b09e-ed35ccf1914a)

![image](https://github.com/user-attachments/assets/ccc2f287-617b-40ff-931c-b8f9788696eb)

![image](https://github.com/user-attachments/assets/a669382a-32bf-4b09-963f-e82004d15dcb)

![image](https://github.com/user-attachments/assets/51e8cfc9-8c98-4dd5-9a27-0da11937ffee)

```
The algorithm selects nodes with the lowest F cost. But if the 2 nodes have the same F cost, the algorithm selects the one with the lowest H cost.

Let's watch the actual path finding based on the Heuristic calculations
```

[![Algorithm](https://img.youtube.com/vi/-L-WgKMFuhE/0.jpg)](https://youtu.be/-L-WgKMFuhE?t=75 "A* Algorithm")


```
A* in action on a real-world graph
```

![](https://github.com/user-attachments/assets/7e2ad18d-6e4d-4c34-82a2-d076e25dbcb0)

```
Who can stall the A* Algorithm from reaching its target wins :)
(Time Taken and Number of Operations)

Only 1 Rule:
1. There should be a path to reach the target

```
/Users/saurabh/Documents/saurabh/DCS/PathFinding.js-master/visual/index.html



</span>
