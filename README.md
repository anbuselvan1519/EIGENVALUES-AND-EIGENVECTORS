# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy library as np variable
### Step 2: make an array of matrix elements
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print the eigenvalue and eigenvector 

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Anbuselvan.S
#RegisterNumber: 23005959
import numpy as np
m=np.array([[4,2],[2,4]])
a,b=np.linalg.eig(m)
print("Eigen values are",a,"and Eigen Vectors are",b)
## Output:
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
```

## Output:
![Screenshot 2023-12-25 110529](https://github.com/anbuselvan1519/EIGENVALUES-AND-EIGENVECTORS/assets/139841744/3680cbe9-1dcb-475f-a381-504c18aaab78)

## Result:
The program was completed successfully.
