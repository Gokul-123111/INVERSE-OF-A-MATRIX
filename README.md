# INVERSE-OF-A-MATRIX
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
```
import numpy as np

matrix = np.array([[1, 0, 3], 
                   [-1, 2, -2], 
                   [2, 3, -1]])


inverse_matrix = np.linalg.inv(matrix)
print(inverse_matrix)

```
## Output:
![Screenshot 2025-03-27 225853](https://github.com/user-attachments/assets/dab34aba-a869-4524-a771-0bcc23a5491d)



# Developed by: Gokul S
# RegisterNumber:212224240044
## Result:
Thus the inverse of given matrix is successfully solved using python program

