# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step 1: 
Import the NumPy library.

### Step 2: 
Create a matrix using np.array().

### Step 3: 
Using np.linalg.eig(), obtain the eigenvalues and eigenvectors of the given matrix.

### Step 4: 
Print the eigenvalues and eigenvectors.

## Program:

~~~python
#Program to find the eigen values and eigen vectors.
#Developed by: Aman Nair
#RegisterNumber: 212225240008

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a= np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
~~~

## Output:

<img width="1253" height="447" alt="image" src="https://github.com/user-attachments/assets/5e6d8df1-7d10-4836-b9b7-863ba54fa187" />
<img width="1224" height="430" alt="image" src="https://github.com/user-attachments/assets/71070f10-33c1-4efe-a60c-7e38ec301974" />

## Result:

Thus the Eigenvalue and Eigenvector is successfully solved using python program
