# Part 1 : turning graphs into adjacency lists and matrices

Given the following graphs, create their adjacency matrices and adjacency lists:

If the graphs below are not visible, switch to the parent directory, go to the directory called www and find graph_1.JPG and graph_2.JPG.

## Graph 1:
![kite](../Assignments/www/graph_1.JPG)

## Graph 2:
![unbalanced tree](../Assignments/www/graph_2.JPG)

## Graph 3: random directory logic

You are given a bunch of files and folders. **Draw a graph of the files and folders**, and also create a modified adjacency matrix **or** list (note that for graph three you only need to supply one of these). The modification here is that there is an additional flag for each node. If the node is a directory, add a d flag and if it is a file add and f flag

Example:

```

[...
    node: my_folder     | edges: 1,2,3  |flag: d
    node: my_file.txt   | edges:        |flag: f
...]

```
There are two nodes listed above where one is a directory and another is a file.

Files and directories:

```

/bin/login.sh
/bin/logout.sh
/users/ariel/life.game
/users/thedude/bowling.png
/exe/brains.load
/history/news/2-18-22.md
/assignments/assignment1.txt
/assignments/solutions.all

```

## For the graphs above answer these questions:

Is the graph a tree? why or why not (if it is, prove why, if it isn't give a proof by contradiction)?



