# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: jeevanesh
#RegisterNumber:23013802
impo![Screenshot (1)](https://github.com/plotswag/EIGENVALUES-AND-EIGENVECTORS/assets/145822344/7fd8c7cb-87ed-4ef9-a33b-eb2267b2aa03)
rt numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
```
![Screenshot (1)](https://github.com/plotswag/EIGENVALUES-AND-EIGENVECTORS/assets/145822344/5022d87a-af8b-4fc1-a468-3c609fb2b1a1)
```
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
