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
<img width="1149" height="779" alt="MA program #4" src="https://github.com/user-attachments/assets/19883084-db95-445d-b44c-00fa923dcc82" />
<img width="1136" height="307" alt="MA program #4 1" src="https://github.com/user-attachments/assets/da5355c8-1732-4513-86b1-82ac03d64362" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
