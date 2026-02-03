# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: S.Abdul Kadher
#RegisterNumber:25015996
import numpy as np
A=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
<img width="1274" height="708" alt="AdobeExpressPhotos_cce7e9db93b84db784589c457caa8602_CopyEdited" src="https://github.com/user-attachments/assets/1e62356c-5a81-4aa3-8a5a-0251cb87f64d" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
