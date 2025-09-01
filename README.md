# LU Decomposition 
## Devoloped by: AKASH G
## Register Number: 212224100004
## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
```
1:Define the package as scipy.linalg import lu.
2:Get input from user and print L and U matrix by 'print' .
3:Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4:print the variable 'X'
```
## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: AKASH G
RegisterNumber: 212224100004

import numpy as np 
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: AKASH G
RegisterNumber: 212224100004

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
```

## Output:
<img width="1452" height="639" alt="image" src="https://github.com/user-attachments/assets/9bcd9d79-b0da-4b80-946d-ab165a744fb0" />
<img width="1446" height="604" alt="image" src="https://github.com/user-attachments/assets/8535bd71-56f4-46e5-8bdf-86e530b6544b" />
<img width="1467" height="879" alt="image" src="https://github.com/user-attachments/assets/b257dbd8-41b4-4da6-ae71-0bfc5683b020" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

