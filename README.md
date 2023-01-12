# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation.
### Step 2: Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
``
#Program to find the eigen values and eigen vectors.
#Developed by: Selva Kumar A
#RegisterNumber:22009007
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors =np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
file:///home/sec/Pictures/Screenshots/Screenshot%20from%202023-01-12%2021-40-45.png![image](https://user-images.githubusercontent.com/120643262/212120742-407555ec-ea2e-4aa5-9933-b0c84245d053.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
