# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step1 :
Import the numpy module to use the built-in functions for calculation.
## Step 2:
Prepare the lists from each equations and assign in np.array()
## Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
## Step 4:
End the program

## Program:
```
import numpy as np
A=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
<img width="1920" height="1080" alt="Screenshot (154)" src="https://github.com/user-attachments/assets/cd0045d5-d29c-4a46-81e8-a4238c9483b4" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
