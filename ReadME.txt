The command structure to run this project is 

$ python3 dijkstra-pathplanning-Thomas-Birney.py start_row,start_col goal_row,goal_col padding

example: $ python3 dijkstra-pathplanning-Thomas-Birney.py 100,60 210,50 5

The origin is the bottom left hand corner of the board. And corrdinates are zero indexed. So the highest
corrdinate possible is 249,399.

Make sure there are no spaces except for in between arguments. Start location and goal location paramters are
required, but the padding paramter is optional. It can be specified as a positive number, or it can be unspecified 
and will be defaultly set to have a padding of 5. It also important to note that start and goal location parameters 
must be within the bounds of the board as well as not point to an obstacle or padded cell.

If all paramters are valid, then the program will create the board, search through it, and animate the search
pattern as well as the shorest path from start to goal. The animation file will be called "search.avi"

Black is unexplored
White is explored
Blue is obstacle
Red is padding/margin


github link to the repository is

https://github.com/Tbirney/dijkstra_project