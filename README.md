# A* Path Finder Algorithm
![Python][1] ![PyGame][2]

#### A GUI based Visualizer of the A* Path Finding Graph Algorithm 
   
Every time the program is executed, a random grid is created and the user can mark the Start and End Points on the grid for the algorithm to search from-Source to-Desination.     
Once the the user has marked the Start and End Points, the user can then place obstacles on the grid by (left-click)dragging anywhere on the grid.
   You can also press the `r` key to load random obstacles into the grid.
   After the obstacles are placed, the user can then press the spacebar.

This will commence a visual that demonstrates how the A* path finding algorithm is searching for the Dest node.
Finally if the Dest node is reached from Source, The optimal path using the A* algorithm will be displayed on the grid.

You can also press the `c` key to clear up the board for a new Entry.

## Controls
| Keys              | Actions                                                        |
|-------------------|----------------------------------------------------------------|
| `Left Click`      | 1st to mark the Source node on grid, 2nd time for Dest node    |
| `r`               | Load Random Obstacles into the grid                            |
| `Space`           | Find the Optimal Path from source to dest using A* path        |
| `c`               | Clear up the board for a new Entry                             |

## Run in Gitpod
You can also alternatively run Sudoku-GUI-Solver in Gitpod, a free online dev environment for GitHub:      
[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/SinisterSup/A.star-Path-Finder-Algorithm/blob/main/a-star.py)

## Alternative Instructions    
If you want to run the game GUI locally on your machine then you need `python` installed on your machine.      
`python -m pip install pygame` in the command prompt to install the dependency needed.        
Voila that's all you need!...            
Now you can just clone the repo remotely on your PC or just download the zip file of this repo wherever on your PC and then just double click on `A-star.exe` 
which is an executable file. This brings up the game window!
##  Enjoy visualizing the A* star algorithm



[1]: https://img.shields.io/badge/Python-v3.10-informational 
[2]: https://img.shields.io/badge/PyGame-v2.1.2-green