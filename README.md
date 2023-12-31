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
Program to find L and U matrix using LU decomposition.
Developed by: P PARTHIBAN
RegisterNumber: 23007965


import numpy as np 
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: P PARTHIBAN
RegisterNumber: 23007965

To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A= np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)
```

## Output:
![image](https://github.com/23007965/LU-Decomposition/assets/138971238/4db23756-9ac4-465a-b7da-1fbb6c89be22)

![image](https://github.com/23007965/LU-Decomposition/assets/138971238/fe13ac1c-3dc7-4539-9b4f-c95aa8381c67)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

