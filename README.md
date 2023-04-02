# COMP2230
University of Newcastle - Algorithms - 2022

Algorithms explored several important algorithms and datastructures looking at how they worked, their effeciency and their common uses.

This repository contains

  - Assignment 1: A program which both generates and solves mazes
  - Playground: A fun place where all of the algorithms taught across the course are implemented and tested. There is no serious structure to this folder. 

## Maze Assignment

The maze generates images as follows

### Image Composition
	- Yellow represents the solution path
	- Red is the start node
	- Green is the finish node 
	- Black represents a wall
	- Each node has a 1 pixel gap from the next and the image border (not a 0 pixel gap). 

### Image Location
	- Maze Images are outputted in the same directory as the input files
	- For example 'java MazeGenerator 10 10 my-folder/out.dat' would output the image to my-folder/maze.bmp
	- Another example, 'java MazeSolverBFS ./out.dat' would output the image to ./solution.bmp

### Viewing Maze Images
	- Windows default app "photos" can be used to view the image but it may be blurry
	- Instead you can open the image in MS Paint, if you do this just make sure your paint brush (the cursor) is not in the way! This may make it look like there is a wall when there isn't!!!
	- Alternatively if you are using IntelliJ it has a really good bitmap viewer. 

## Building

```sh
javac MazeGenerator.java
javac MazeSolverBFS.java
```

Running
Use command line arguments for input e.g.

```sh
java MazeGenerator 5 6 maze.dat
java MazeSolverBFS maze.dat
````
