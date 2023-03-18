# RANK-OF-A-MATRIX

## Aim:
To write a python program to find the rank of a matrix

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
### Step 1:
Import numpy as np
### Step 2: 
Assign the values of the matrix to a variable using np.array
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix
### Step 4:
Use print() function to display the rank of the matrix

## Program:
```
#Program to find the rank of a matrix.
#Developed by: Sneha Basyal M
#RegisterNumber:212222240101

import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(A)
print(rank)
```
## Output:
![RANK-OF-A-MATRIX](put.png)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

