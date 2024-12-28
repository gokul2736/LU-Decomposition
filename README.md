# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Take values from user
3. Write the code without any error
4. End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: M.GOKUL
RegisterNumber: 24000042
import numpy as nu
from scipy.linalg import lu
a=nu.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: M.GOKUL
RegisterNumber: 24000042
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
A=np.array(a)
B=np.array(b)
result=lu_factor(A)
sol=lu_solve(result,B)
print(sol)
*/
```

## Output:
![image](https://github.com/user-attachments/assets/c73b0b8d-8533-42fb-9997-96a6f8282bc5)
![image](https://github.com/user-attachments/assets/67672c8d-6af4-43b1-98b6-964d614a9d70)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

