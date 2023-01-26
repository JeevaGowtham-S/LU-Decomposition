# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. Prepare the lists from each linear equations and assign in np.array()
3. Using the lu() function in scipy.linalg module, we can find the solutions.
4. End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: JEEVA GOWTHAM S
RegisterNumber: 22008760
*/

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
Developed by: JEEVAGOWTHAM S
RegisterNumber: 22008760
*/

import numpy as np
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)

```

## Output:
i)
![LU1](https://user-images.githubusercontent.com/118042624/214773304-ac4fe490-5301-45ab-a1dc-c2fadd12b327.png)
ii)
![LU2](https://user-images.githubusercontent.com/118042624/214773369-5cfa7b73-1102-42d4-a697-e2a110bfd95d.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

