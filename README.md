# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.  Import the numpy module to use the built-in functions for calculation
2. from scipy.linalg import lu we can find L and U
3. print L and U
4. end the program
  

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
*/
'''Program to find L and U matrix using LU decomposition.
Developed by:A.Sesank
RegisterNumber:23009543 
'''
import numpy as np
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
*/
'''Program to solve a matrix using LU decomposition.
Developed by:A.Sesank 
RegisterNumber: 23009543
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)

```

## Output:
![image](https://github.com/ALLAMSESANK/LU-Decomposition/assets/147120920/ac8499af-eeb2-413f-ad3c-56756c5b0e99)
![image](https://github.com/ALLAMSESANK/LU-Decomposition/assets/147120920/ad06e37c-ad69-4349-bfd9-78fa9c72673b)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

