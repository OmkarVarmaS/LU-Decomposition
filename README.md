# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
 1.Define the package as scipy.linalg import lu.
 2. Get input from the user and print L and U matrix by 'print'.
 3. Define the package as "from scipy.linalg import import lu_factor, lu_solve, lu_solve" and create the
 variable as 'X' include the package in that variable.
 4. Print the variable 'X'

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: OMKAR VARMA S
RegisterNumber: 212224240108
'''

import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U) 
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by:OMKAR VARMA S 
RegisterNumber: 212224240108
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
*/
```

## Output:
<img width="1334" height="1021" alt="{F29E0F53-C8FB-45FF-8A98-D0A76A97A275}" src="https://github.com/user-attachments/assets/dde9033f-1165-4d24-9b36-e1dbb56b5efd" />


<img width="1298" height="932" alt="{58446EFD-DDAF-4BC1-9742-56A65F9E1EC0}" src="https://github.com/user-attachments/assets/3d99fc14-048d-4f76-93c6-a3fbfc5f6e3b" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

