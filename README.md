# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

### Step 1:
Import numpy package 
### Step 2:
Give the elements in the matrix
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End the program

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by:Shakthi Kumar S 
#RegisterNumber:22009242
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
b,c=np.linalg.eig(a)
print("Eigen values are",b,"and Eigen Vectors are",c)
```

## Output:
![](Maths%20Exp04%20Shakthi%20kumar%20S%20(22009242).png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
