# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from the matrix and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.

## Program:
```
import numpy as np
A = np.array([[-2, 2, -3],[2, 1, -6],[-1, -2, 0]])
eigenvalues, eigenvectors = np.linalg.eig(A)
print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)
```
## Output:
<img width="1279" height="820" alt="Screenshot 2025-09-03 121057" src="https://github.com/user-attachments/assets/b2db332d-f885-4505-be10-c3d38f24ae11" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
