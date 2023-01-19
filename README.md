# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step1 : import numpy as np
## Step 2: arrange the given matrix in np.array command
## Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
## Step 4: run the program and get the output


## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: bejin
#RegisterNumber:2001908
import numpy as np
a=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
## Output:
![image](https://user-images.githubusercontent.com/118367518/213353662-5a24eb0c-39df-42d6-8f09-9704b3ce079c.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
