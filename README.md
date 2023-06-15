# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1: Import numpy library using import statement.

Step 2: From scipy package import lu().

Step 3: Get input from user and pass it as an array.

Step 4: Get P, L, U matrix using lu()

Step 5: Print L and U matrix

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Chandrasekar S
RegisterNumber: 212222230025
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
Developed by: Chandrasekar S
RegisterNumber: 212222230025
*/


# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
B=np.array([4, 5, 7])
LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)

```

## Output:
## find the L and U matrix:
![image](https://github.com/ChandrasekarS22008273/LU-Decomposition/assets/119643845/de1c98ec-4887-4b5b-b3a0-5834cfa2564e)

## find the LU Decomposition of a matrix:
![image](https://github.com/ChandrasekarS22008273/LU-Decomposition/assets/119643845/866e136e-509b-416b-bfa8-a154e70b3842)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
