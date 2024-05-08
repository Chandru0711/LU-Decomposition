# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.
2.Get input from user and print L and U matrix by 'print' .
3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4.print the variable 'X'

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: CHANDRU SM
RegisterNumber: 212223230034
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: CHANDRU SM
RegisterNumber: 212223230034
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
B=np.array(eval(input()))
C=np.linalg.solve(A,B)
print(C)

*/
```

## Output:
![Screenshot 2024-05-08 232929](https://github.com/Chandru0711/LU-Decomposition/assets/144979368/a120567e-34b5-4cfc-8694-9db2e63f7801)

![Screenshot 2024-05-08 232950](https://github.com/Chandru0711/LU-Decomposition/assets/144979368/1426291f-b995-4b1c-b739-91b3edb3e70c)

![Screenshot 2024-05-08 233134](https://github.com/Chandru0711/LU-Decomposition/assets/144979368/f9d4d7c9-d5d4-4b75-afeb-b4e88dc2fe68)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

