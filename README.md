# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

 1. Import numpy extention and scipy.linalg extension
 2. Initialize the matrix values
 3. Use lu functions from imported extension
 4. Print the output

## Program:
(i) To find the L and U matrix
/*
Program to find the L and U matrix.
Developed by: MANO KARTHICK S
RegisterNumber: 212222230077
*/
```
import numpy as np  
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu,piv = lu_factor(A)
X = lu_solve((lu,piv),b)
print(X)


```
(ii) To find the LU Decomposition of a matrix

/*
'''Program to solve a matrix using LU decomposition.
Developed by:MANO KARTHICK S
RegisterNumber: 212222230077
*/
```
import numpy as np  
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu,piv = lu_factor(A)
X = lu_solve((lu,piv),b)
print(X)
```

## Output:
![image](https://github.com/MANOKARTHICK09/LU-Decomposition/assets/121785458/a5957cc7-57e3-43e7-8020-71c43129ea2c)
![image](https://github.com/MANOKARTHICK09/LU-Decomposition/assets/121785458/cc45931d-7e3c-4f2b-a431-433b82ac8650)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

