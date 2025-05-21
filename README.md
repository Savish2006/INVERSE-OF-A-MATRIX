# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
Step 1: Start the program.

Step 2: Import the NumPy library using import numpy as np.

Step 3: Define a 3x3 matrix a using np.array().
  Example: a = np.array([[2,1,1],[1,1,1],[1,-1,2]]).

Step 4: Use the NumPy function np.linalg.inv() to compute the inverse of the matrix a.
  Store the result in variable b.
  Example: b = np.linalg.inv(a).

Step 5: Print the inverse matrix b.

Step 6: End the program.
```
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

