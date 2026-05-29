# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
step 1: Import the required libraries numpy and scipy.linalg. Step 2: Define the input matrix A.

Step 3: Apply the lu() function to decompose matrix A into P, L, and U matrices.

Step 4: Display the lower triangular matrix L and upper triangular matrix U.

Step 5: Stop the program.

## Program:
(i) To find the L and U matrix.
```
Developed by: DWIJESH RAJ SINHA Y
RegisterNumber: 212225240038
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A =np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: DWIJESH RAJ SINHA Y
RegisterNumber: 212225240038
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix= np.array(eval(input()))
constant =np.array(eval(input()))
piv,lu=lu_factor(matrix)
result=lu_solve((piv,lu),constant)
print(result)
```

## Output:
<img width="1211" height="549" alt="image" src="https://github.com/user-attachments/assets/08d62920-c4a4-4f03-b2d5-da4254b758a6" />
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

