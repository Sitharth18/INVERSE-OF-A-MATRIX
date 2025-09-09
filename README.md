INVERSE-OF-A-MATRIX
Aim:
To write a python program to find the inverse of a matrix

Equipment’s required:
Hardware – PCs
Anaconda – Python 3.7 Installation / Moodle-Code Runner
Algorithm:
Step1 :
Import the numpy module to use the built-in functions for calculation

Step 2:
Prepare the lists from the matrix and assign in np.array()

Step 3:
Use the np.linalg.inv() fun

Step 4:
End the program.

Program:
#Program to find the inverse of a matrix.
#Developed by: Sitharth B S
#RegisterNumber:212224110048

import numpy as np
matrixA= np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
inverse= np.linalg.inv(matrixA)
print(inverse)
Output:
<img width="1320" height="843" alt="Screenshot 2025-09-09 135552" src="https://github.com/user-attachments/assets/9ed8e231-3253-4dfc-b231-36d5e4c24a04" />


Result:
Thus the inverse of given matrix is successfully solved using python program
