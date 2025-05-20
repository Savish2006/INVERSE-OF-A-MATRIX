# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Check if the matrix is square.

### Step 2:
Calculate the determinant.

If det = 0, inverse doesn't exist.

### Step 3:
Find the cofactor matrix.
### Step 4 :
Transpose the cofactor matrix → gives the adjoint.

### Step 5 :
Divide adjoint by determinant method
### Step 6 :
END OF PROGRAM 
## Program:
```
#Program to find the inverse of a matrix.
#Developed by: SAVISH R
#RegisterNumber:212224230257

import numpy as np
a=np.array([[2,1,1],[1,1,1],[1,-1,2]])
b=np.linalg.inv(a)
print(b)
```
## Output:

![image](https://github.com/user-attachments/assets/40b08cd3-a969-4dbc-8ecd-ff41035234bf)

## Result:
Thus the inverse of given matrix is successfully solved using python program

