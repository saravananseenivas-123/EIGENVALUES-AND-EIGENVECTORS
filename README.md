# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program


## Program:
~~~

import numpy as np
A = np.array([[-2,2,-3], 
              [2,1,-6],
              [-1,-2,0]])
values,vectors = np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")

~~~

## Output:

<img width="1149" height="779" alt="Screenshot 2025-11-22 at 20 04 36" src="https://github.com/user-attachments/assets/b217e6af-2f54-4e61-8592-7d3b109e09ff" />
<img width="1136" height="307" alt="Screenshot 2025-11-22 at 20 05 04" src="https://github.com/user-attachments/assets/c7061376-d19a-4948-8b52-025f5333917b" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
