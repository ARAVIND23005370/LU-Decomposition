# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module and scipy.linalg module to use the built-in functions for calculation.
2. Prepare the lists from each linear equations and assign in np.array()
3. Perform scipy.linalg.lu() to find the pivot table, lower traingle and upper triangle matrix.
4. End the Program

## Program:
(i) To find the L and U matrix
```PYTHON
Program to find the L and U matrix.
Developed by: ARAVIND R
RegisterNumber: 23005370
import numpy as np
a=eval(input())
from scipy.linalg import lu
b=np.array(a)
p,l,u=lu(b)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```PYTHON
Program to find the LU Decomposition of a matrix.
Developed by: ARAVIND R
RegisterNumber: 23005370
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
c=eval(input())
b=np.array(a)
d=np.array(c)
l,p=lu_factor(b)
x=lu_solve((l,p),d)
print(x)
```

## Output:
![Screenshot 2023-12-28 212726](https://github.com/ARAVIND23005370/LU-Decomposition/assets/148514836/f5217530-960a-4190-a52c-8780bb059fbb)
![Screenshot 2023-12-28 212736](https://github.com/ARAVIND23005370/LU-Decomposition/assets/148514836/22b739df-3fff-41f1-8774-ad6ac7df902e)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

