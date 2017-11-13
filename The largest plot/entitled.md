# The Largest plot
> You need to find a plot to keep your sheeps but there are rocks obstructing your field and sheeps hate rocks, so you want to give your them the largest plot possible without rocks inside it.

----------

### Rules :
- A plot is always a square and have a minimum of 1m*1m size (1m*1m = 1 char)
- In the data files:
	- A `"\n"` correspond to 1m
	- One `'.'` is nothing and one `'X'` is an obstacle
- No obstacles in the plots
- If there are more than one plot finded, show the others plot (With output for each plot founded)
- You can just use the given data files to create this algorithm

#### The output :
- An output file with the largest plot replaced by `'O'` instead of `'.'` (Obstacle and outside the plot will be the same as the data file)
- Four values
	- The Y axis in the file
	- The X axis in the file
	- The size S of the plot

### Examples:
#### 1 :
This input :
```
.X..X
...X.
.X...
...X.
.....
```

Will become this ouput :
```
.X..X
...X.
.X...
OO.X.
OO...

Y: 4
X: 1
S: 2
```


----------
#### 2 :
This input :
```
...X...
.......
...X...
.X.X...
.....X.
...X...
.......
```

Will become this ouput :
```
OOOXOOO
OOO.OOO
OOOXOOO
.X.XOOO
OOO..X.
OOOX...
OOO.OOO

1---
Y: 1
X: 1
2---
Y: 1
X: 5
3---
Y: 2
X: 3
4---
Y: 5
X: 1

------
S: 3
```
