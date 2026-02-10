# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions
2. Prepare the lists from each linear equations and assign in np.array(eval(input()))
3. Using the lu_solve ,we can find the solutions
4. End the program.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: SANJAI K
RegisterNumber: 212225230245
import numpy as np
from scipy.linalg import lu
matrix=eval(input())
P,L,U=lu(matrix)
print(L)
print(U)

*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: SANJAI K
RegisterNumber: 212225230245
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
constant=np.array(eval(input()))
piv,lu=lu_factor(matrix)
result=lu_solve((piv,lu),constant)
print(result)

*/
```

## Output:
![lu decomposition](Screenshot%202026-02-10%20101119.png)
![lu decomposition](Screenshot%202026-02-10%20101119.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

