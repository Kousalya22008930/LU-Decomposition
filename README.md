# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module and scipy.linalg module to use the built-in functions for calculation.
2. Prepare the lists from each linear equations and assign in np.array().
3. Perform scipy.linalg.lu() to find the pivot table, lower traingle and upper triangle matrix.
4. End the Program.

## Program:
(i) To find the L and U matrix
```
#Program to find L and U matrix using LU decomposition.
#Developed by: KOUSALYA A.
#RegisterNumber: 212222230068


import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix

```
Program to solve a matrix using LU decomposition.
Developed by: KOUSALYA A.
RegisterNumber: 212222230068

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
b=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![image](https://github.com/Kousalya22008930/LU-Decomposition/assets/119389108/0f9954b9-2b46-4dfe-9a7a-299b5c2f38ef)
![image](https://github.com/Kousalya22008930/LU-Decomposition/assets/119389108/5b9449d7-bab7-45d1-b6b1-e59b4954905f)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

