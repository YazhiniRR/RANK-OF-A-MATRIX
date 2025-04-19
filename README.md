# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Start Create matrix A
### Step 2: Apply a matrix rank finding method (such as row echelon form or singular value decomposition) to determine how many linearly independent rows or columns the matrix has.
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Store the result in result,Print the value of result.This is the rank of matrix A.
## Program:
```
import numpy as np
A=np.array([[1,2,3],[3,6,9]])
result=np.linalg.matrix_rank(A)
print(result)
```
## Output:
![Screenshot 2025-04-19 152624](https://github.com/user-attachments/assets/78aa0c6b-eb7f-4990-860c-c59ae2a6da7c)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

