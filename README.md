# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
Define the package as scipy.linalg import lu. 2.Get input from user and print L and U matrix by 'print' . 3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable. 4.print the variable 'X'

## Program:
(i) To find the L and U matrix
```'''Program to find L and U matrix using LU decomposition.
Developed by: Mohanram Gunasekar
RegisterNumber: 212223240095
'''
import numpy as np
from scipy.linalg import lu

A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Mohanram Gunasekar
RegisterNumber: 212223240095
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve

A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
```

## Output:
![Screenshot 2024-05-19 151126](https://github.com/MohanramGunasekar/LU-Decomposition/assets/139841812/62ad783c-d7e6-475e-9f27-8a2e158288f5)
![Screenshot 2024-05-19 151134](https://github.com/MohanramGunasekar/LU-Decomposition/assets/139841812/1e8e69f6-855b-4f1c-a7d4-c50fd01c974c)
![Screenshot 2024-05-19 151140](https://github.com/MohanramGunasekar/LU-Decomposition/assets/139841812/7a8d4569-ba49-4159-aa8c-0f26343eaa84)
![Screenshot 2024-05-19 151146](https://github.com/MohanramGunasekar/LU-Decomposition/assets/139841812/c42354fc-75ce-4d03-98a9-6407d0f77f41)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

