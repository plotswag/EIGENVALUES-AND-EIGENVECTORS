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
Get the input matrix from the user
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End the program 

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: jeevanesh
#RegisterNumber:23013802
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![image](https://github.com/plotswag/EIGENVALUES-AND-EIGENVECTORS/assets/145822344/41348328-cff6-4505-93a0-8500178c81e6)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
