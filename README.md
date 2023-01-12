# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: JAYAVARTHAN P
RegisterNumber: 22008689

import numpy as np
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)

*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)

*/
```

## Output:
![lu decomposition]()
![Screenshot (5)](https://user-images.githubusercontent.com/121369281/212130872-993900d0-79d4-4955-a6db-84daeda1a99a.png)
![5 2 EDM_page-0001](https://user-images.githubusercontent.com/121369281/212130877-c18a5ca6-b76f-4332-85b0-fb3c8feb6130.jpg)

![Screenshot (6)](https://user-images.githubusercontent.com/121369281/212130925-782a4d41-948d-4e8d-8f60-13ae6fd8737f.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

