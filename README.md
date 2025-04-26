# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
 1. Import required libraries numpy and scipy.linalg. 2.Input the matrix/matrices
 using eval(input()). 3.Perform LU decomposition using lu() or solve equations
 using lu_factor() and lu_solve().
 2. Print the results L and U matrices or solution X matrix 

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: RITHIKA L
RegisterNumber: 212224230231
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by:RITHIKA L 
RegisterNumber: 212224230231
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)

```

## Output:
![lu decomposition]()
![Screenshot 2025-04-26 134557](https://github.com/user-attachments/assets/79b5a8e1-c9c2-4219-a653-06f3c90ba94a)

![lu decomposition matrix]()
![image](https://github.com/user-attachments/assets/3546f1a5-5e20-40b0-9db2-6d570701658a)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

