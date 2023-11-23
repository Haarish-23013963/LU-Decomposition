# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import libraries:scipy.linalg,numpy.
2. Read and evaluate arrays from user.
3. Use LU decomposition and solve the system.
4. Print the solution.

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Haarish.V
RegisterNumber: 23013963
'''
from scipy.linalg import lu
import numpy as np

arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Haarish.V
RegisterNumber: 23013963
'''

# To print X matrix (solution to the equations)
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
```

## Output:
### (i) To find the L and U matrix
![output](/output2.png)
### (ii) To find the LU Decomposition of a matrix
![output](/output1.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

