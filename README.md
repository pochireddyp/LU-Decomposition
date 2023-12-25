# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.import the numpy as np
2.from scipy.linalg import lu
3.enter the lists from each linear equationa and assgin in np.array()
4.using lu( )and store it in three variables
5.print the L and U matrix
6.end the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: pochireddy.p
RegisterNumber: 23006090
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: pochireddy.p
RegisterNumber: 23006090
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)


*/
```

## Output:
![image](https://github.com/pochireddyp/LU-Decomposition/assets/150232043/a0facebc-688b-4272-a4bf-c6e72f8fa088)
![image](https://github.com/pochireddyp/LU-Decomposition/assets/150232043/8f5f55af-c3f3-4d56-bd51-dc3cb07bcbfb)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

