# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## STEP 1:Import Required Libraries
      Import the required libraries:
      numpy for matrix creation
      scipy.linalg.lu for LU decomposition
      
## STEP 2: Input the Matrix
      Prompt the user to input a square or rectangular matrix in the format of a nested list (e.g. [[1, 2], [3, 4]]).
   
## STEP 3: Perform LU Decomposition
      Call the lu() function from scipy.linalg, which returns:
      P: Permutation matrix (tracks row swaps)
      L: Lower triangular matrix (with 1s on the diagonal)
      U: Upper triangular matrix
## STEP 4: Display the Result
      Print the L (lower triangular) and U (upper triangular) matrices:

## Program:
(i) To find the L and U matrix
```import numpy as np
from scipy.linalg import lu

A = np.array(eval(input()))
P, L, U = lu(A)

print(L)
print(U)

/*
Program to find the L and U matrix.
## Developed by: S.MOULIDHARAN
## RegisterNumber: 212224240095
*/
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input("(e.g. [[1,2],[3,4]]): ")))
P, L, U = lu(A)
print("Lower triangular matrix L:")
print(L)
print("\nUpper triangular matrix U:")
print(U)

/*
Program to find the LU Decomposition of a matrix.
Developed by: S.MOULIDHARAN
RegisterNumber: 212224240095
*/
```
## Output:
![image](https://github.com/user-attachments/assets/7e89180a-47e4-4b96-8774-7790e290de19)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

