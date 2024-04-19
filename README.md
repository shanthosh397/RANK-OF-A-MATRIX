Date:09-03-2024
# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
importing the NumPy library using the statement import numpy as np.
### Step 2: 
Define a 3x3 matrix A with the specified values.
### Step 3: 
Compute the rank of matrix A using the np.linalg.matrix_rank() function.
### Step 4: 
Display the rank of matrix A using the print() statement.
### Step 5: 
End the program.
## Program:
```
#Developed by:Shanthosh.G
#Register Number:2305003008

import numpy as np
A = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank = np.linalg.matrix_rank(A)
print(rank)
```
## Output:
![Screenshot 2024-04-19 223406](https://github.com/shanthosh397/RANK-OF-A-MATRIX/assets/153431200/144d58c9-215e-4d06-b778-df8da1d6af09)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

