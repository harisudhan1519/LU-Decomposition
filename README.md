# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner


##Algorithm:
Step 1 Import the numpy module to use the built-in functions for calculation

Step 2 Prepare the lists from each linear equations and assign in np.array()

Step 3 Using the np.linalg.solve(), we can find the solutions.

Step 4 End the program
   
 

## Program:
1.to find L and U using LU decomposition
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```

2.to solve matrix using LU decomposition
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
```

## Output:
![image](https://github.com/user-attachments/assets/5a8ef4dc-ddda-473a-84b3-6b3bbe36a929)
![image](https://github.com/user-attachments/assets/d9aaf9ec-0756-45eb-8ebd-d4f3f2cec3a2)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

