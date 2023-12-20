# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : importing numpy function
### Step 2: assigning values to the variable in list form
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: using print function print the eigen values

## Program:#Program to find the eigen values and eigen vectors.
~~~
#Developed by: DEVESH S

#RegisterNumber:23004345

import numpy as np

a=[[2,-3,0],[2,-5,0],[0,0,3]]

b,c=np.linalg.eig(a)

print("Eigen values are",b,"and Eigen Vectors are",c)
~~~

## Output:![Screenshot 2023-12-19 220056](https://github.com/23004345/EIGENVALUES-AND-EIGENVECTORS/assets/138849203/34590b54-a5d9-4002-8c5a-1d83d2364c8a)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
