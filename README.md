# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
import numpoet as np 
### Step 2:
Assign in np.array() in eigen values and eigen vectors of matrix 
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
print the value and end the program

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by:Ragavendran A 
#RegisterNumber:22008885
import numpy as np
from numpy.linalg import eig
a=np.array([[2,2],[1,3]])
w,v=eig(a)
print("Eigen values are",w,"and Eigen Vectors are",v)
```

## Output:
![output](/output2.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
