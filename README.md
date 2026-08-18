# Exp 2 - INVERSE-OF-A-MATRIX
### Developed by : Deepak K R
### RegisterNumber : 212225040057


## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:


1. **Import Dependencies:** Load the `numpy` library to enable matrix data structures and mathematical operations.
2. **Initialize the Matrix:** Define the target 3x3 square matrix using a two-dimensional array (`np.array`).
3. **Compute the Inverse:** Calculate the multiplicative inverse of the matrix using NumPy's linear algebra module (`np.linalg.inv`).
4. **Display the Output:** Print the resulting inverse matrix to the console for verification.

## Program:

```py
#Program to find the inverse of a matrix.
#Developed by: Deepak K R
#RegisterNumber: 212225040057

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
matrix = np.array([[2,1,1],[1,1,1],[1,-1,2]])
inverse = np.linalg.inv(matrix)
print(inverse)
```

## Output:

<img width="1075" height="331" alt="Screenshot 2026-08-18 093443" src="https://github.com/user-attachments/assets/76948bcc-c2f3-4200-99e1-c1b06671060a" />


## Result:
Thus the inverse of given matrix is successfully solved using python program

