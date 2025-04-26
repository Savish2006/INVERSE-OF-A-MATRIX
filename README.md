# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1: Start
Step 2: Input the matrix
Take a square matrix (same number of rows and columns).

Step 3: Check if the matrix is invertible
Calculate the determinant of the matrix.

If the determinant is 0, the matrix is not invertible (stop here).

If the determinant is not 0, proceed to find the inverse.

Step 4: Find the adjoint (adjugate) of the matrix
Find the cofactor matrix.

Take the transpose of the cofactor matrix to get the adjoint matrix.

Step 5: Calculate the inverse
Use the formula:

Inverse of matrix
=
1
Determinant
×
Adjoint matrix
Inverse of matrix= 
Determinant
1
​
 ×Adjoint matrix
Step 6: Output the inverse matrix 

## Program:
#Program to find the inverse of a matrix.
#Developed by: SAVISH R
#RegisterNumber:212224230257
import numpy as np
a=np.array([[2,1,1],[1,1,1],[1,-1,2]])
b=np.linalg.inv(a)
print(b)
## Output:

![image](https://github.com/user-attachments/assets/40b08cd3-a969-4dbc-8ecd-ff41035234bf)

## Result:
Thus the inverse of given matrix is successfully solved using python program

