# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in function for calculation
### Step 2:
Prepare the list from each linear equation and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End of the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:GOWTHAM V
#RegisterNumber:212223100009
import numpy as np

# Define the matrix
matrix = np.array([[2, 2],
                   [1, 3]])

# Find eigenvalues and eigenvectors
eigenvalues, eigenvectors = np.linalg.eig(matrix)

# Print the result
print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)

```

## Output:
![image](https://github.com/Gowtham-jk/EIGENVALUES-AND-EIGENVECTORS/assets/149857834/89b4c94b-d54d-45c2-8362-2dcbb2c9a569)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
