## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 : Import the numpy module to use the built-in functions for calculation

Step 2: Prepare the lists from each equations and assign in np.array()

Step 3: Using the np.linalg.matrix_rank(),we can find the inverse of the given marks

Step 4: End the program.

## Program:
~~~
#Program to find the inverse of a matrix.
#Developed by: Dharshan V
#RegisterNumber: 212224240035

import numpy as np

matrix = np.array([[2, 1, 1], 
                   [1, 1, 1], 
                   [1, -1, 2]])


inverse_matrix = np.linalg.inv(matrix)
print(inverse_matrix)
~~~
## Output:
<img width="1278" height="843" alt="Screenshot 2025-08-25 094407" src="https://github.com/user-attachments/assets/83449e9d-869e-413c-a52c-bbb0f300a23d" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

