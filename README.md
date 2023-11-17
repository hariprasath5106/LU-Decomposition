# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.import numpy package. 
2.import scipy package and use linalg function from lu. 
3.Using three(P,L,U) variables store lu(arr). 
4.print L and U. 
5.End the program.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: HARI PRASATH S
RegisterNumber: 212222240034
*/
import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: HARI PRASATH S
RegisterNumber: 212222240034
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x
```

## Output:
1 
![image](https://github.com/hariprasath5106/LU-Decomposition/assets/111515488/8ae041e3-a437-40cd-a624-799e50910a5a)
2
![image](https://github.com/hariprasath5106/LU-Decomposition/assets/111515488/8c00b1bf-b9c9-4f0a-9176-ebe0b63de35b)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

