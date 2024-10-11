<!-- Link to Google Font -->
<link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swa" rel="stylesheet">


<span style="font-family: 'Montserrat', sans-serif;">

# Session 1 Maze

## Nasa Pathfinder Mission
![image](https://github.com/user-attachments/assets/a757eabc-5223-4ed5-85ba-ffa52e560a14)

## Martian Surface
![image](https://github.com/user-attachments/assets/caa133d0-20a3-4e55-9b82-e735f0800d0c)

## Martian Surface in Video
[![Martian Surface](https://img.youtube.com/vi/9HGRReKUzfU/0.jpg)](https://www.youtube.com/watch?v=9HGRReKUzfU "Martian Surface")

## Pathfinder tasks
Among all the other scientific tasks
- Test communications
- Taking measurements of the atmosphere and imaging the surface

Rover (Named "Sojourner", meaning a temporary resident)
- 280 mm high - About a Foot
- 630 mm long - About 2 Feet
- 480 mm wide - About 1.5 Feet

> Sojourner, The rover was controlled by an operator on Earth, who used images from the rover and lander systems. The operator had to account for a time delay of about 10 minutes, so the rover also had autonomous intelligence for navigating the surrounding MAZE.

# So how did Sojourner moved around on an unknown planet?


> By solving the surrounding maze. 

## Demo Time
![image](https://github.com/user-attachments/assets/4fc1b295-3cef-4b32-9b2d-ce058ecdf8bc)

### We are going to learn about
- Creating Mazes
- Solving them using different Algorithms
- Shifting Mazes


## Lets define a Maze
- is it just a network of paths?


> Typically, a maze has a border and horizontal and vertical lines with a start and a finish.
But where are the lines allowed to me? 

<img width="500" src="https://github.com/user-attachments/assets/f6b89d36-4d17-4f6a-a215-b671da328b0f">


I would say, a maze is a grid of cells with some parts of the lines removed.

> But hold on, which parts are to be removed? 
The thing that makes a maze a maze is that the maze has pathways, so remove the paths that create those pathways 

<img width="500" src="https://github.com/user-attachments/assets/71f4c257-003f-4697-8637-f8a42f95eb4f">

> One way to do this, is to start at a cell and draw a pathway to another cell, remove any segment that got in the way

<img width="500" src="https://github.com/user-attachments/assets/45306891-0323-46ee-a60e-a80148d0e668">

Using this strategy we can make any maze we want

<img width="500" src="https://github.com/user-attachments/assets/f1dbca8b-de78-43c4-aeee-825d0c6c993c">

<img width="500" src="https://github.com/user-attachments/assets/55e86aab-2d78-4108-a338-ae7ec2e1b1fe">

> But can all these be called a good maze?

<img width="800" alt="image" src="https://github.com/user-attachments/assets/faef4e0e-814e-4959-b911-369720029b90">

A good maze is probably the one with more connections. We should be able to get from any point to any other point with one BIG pathway

<img width="800" alt="image" src="https://github.com/user-attachments/assets/d1ff9e1f-c3e5-415a-b9d0-a6b0cbabd441">

> To be more specific, a good maze is when you have ONE option to move from one place to another. Not ZERO, and Not MANY. Therefore having a loop in a maze is not fun because they give us multiple ways to get from A to B.

<img width="500" alt="image" src="https://github.com/user-attachments/assets/9cdec374-69f8-44e0-a809-350189334690">

> Another one is a place in the maze where you can not reach. (Isolated area)

`What does it mean to generate a perfect maze`
> That would mean connecting all the dots such that there is one path from one dot to any other dot. In Computer Science terms, we call that a `Tree` 

Start at any point and randomly start connecting edges. Initially, it will work great, but you are going to see a couple of problems ... can you guess?

[![Maze Generation](https://img.youtube.com/vi/uctN47p_KVk/0.jpg)](https://youtu.be/uctN47p_KVk?t=366 "Maze Generation")

# Maze Generation Algorithms

## Depth First Search (DFS)
- If you are stuck, just go back in time and start from the node that has other unvisited nodes.

[![Depth First Search (DFS)](https://img.youtube.com/vi/uctN47p_KVk/0.jpg)](https://youtu.be/uctN47p_KVk?t=367 "DFS")


## Hunt and Kill (HAK)
- Start from the top and find a node that has other unvisited nodes instead of going back in time. 
 
[![Hunt and Kill (HAK)](https://img.youtube.com/vi/uctN47p_KVk/0.jpg)](https://youtu.be/uctN47p_KVk?t=367 "HAK")

</span>
