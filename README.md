# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: import numpy as np
This line imports the NumPy library and gives it the alias 'np'. NumPy is a powerful library for numerical operations in Python, and it is commonly used for linear algebra operations.
### Step 2: a = [[5, -3, -10], [2, 2, -3], [-3, -1, 5]]
This line creates a 3x3 matrix 'a' using a nested list. Each inner list represents a row in the matrix.
### Step 3: b = np.linalg.matrix_rank(a)
The np.linalg.matrix_rank function is used to calculate the rank of matrix 'a'. The result is 
### Step 4: print(b)
This line prints the calculated matrix rank to the console.
### step 5:
end program.
## Program:
```
#Program to find the rank of a matrix.
#Developed by: Ganesh D
#RegisterNumber:23013987
import numpy as np
a=[[5,-3,-10],[2,2,-3],[-3,-1,5]]
b=np.linalg.matrix_rank(a)
print(b)
```
## Output:
<img width="615" alt="Rank of matrix " src="https://github.com/Ganesh23013987/RANK-OF-A-MATRIX/assets/147473768/0d18cb5b-8c7b-4578-b0c2-0426f3ad68bc">

## Result:
Thus, the rank for the given matrix is successfully solved by  using a python program.

