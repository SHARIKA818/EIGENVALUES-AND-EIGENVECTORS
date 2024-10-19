# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
step1 : Import the numpy module to use the built-in functions for calculation.
Step 2: Prepare the lists from each equations and assign in np.array()
Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
Step 4: End the program

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by:sharika.R
#RegisterNumber:212223230204
import numpy as np
A=np.array([[4,2],[2,4]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are",evalues,"and Eigen Vectors are",evector)

## Output:
![Screenshot 2024-10-19 023207](https://github.com/user-attachments/assets/cc31230b-420a-4637-be65-cf3c7fc98905)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
