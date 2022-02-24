# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: import the numpy module to use the builtin functions for calculation
### Step 2: prepare the lists fron each linear equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: end the program
## Program:
~~~python 
import numpy as np
A=np.array([[1,2,3],[3,6,9]])
s=np.linalg.matrix_rank(A)
print(s)
~~~
## Output:
![matrixlinear](https://user-images.githubusercontent.com/93978702/155522802-a96d8fb9-94de-4b29-aa19-38b5235b474b.jpg)


## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

