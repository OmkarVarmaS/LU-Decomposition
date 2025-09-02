# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
 1.Define the package as scipy.linalg import lu.
 2. Get input from the user and print L and U matrix by 'print'.
 3. Define the package as "from scipy.linalg import import lu_factor, lu_solve, lu_solve" and create the variable as 'X' include the package in that variable.
 4. Print the variable 'X'
## Program:
(i) To find the L and U matrix
```
/*
 Program to find the L and U matrix.
 Developed by: OMKAR VARMA S
 RegisterNumber: 212224240108
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
 Program to find the LU Decomposition of a matrix.
 Developed by: OMKAR VARMA S
 RegisterNumber: 212224240108
import numpy as np
 from scipy.linalg import lu, lu_factor, lu_solve
 a=np.array(eval(input()))
 b=np.array(eval(input()))
 lu_fac, p=lu_factor(a)
 x=lu_solve((lu_fac,p),b)
 P,L,U=lu(a)
 print(x)
*/
```

## Output:

<img width="1334" height="1021" alt="Screenshot 2025-09-02 121431" src="https://github.com/user-attachments/assets/6d47fcd9-3b1f-4f8f-8cb7-5cff23943b9f" />


 <img width="1298" height="932" alt="Screenshot 2025-09-02 121708" src="https://github.com/user-attachments/assets/bf06c75d-d69e-4b7a-bb9b-cebb4ae6efbb" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

