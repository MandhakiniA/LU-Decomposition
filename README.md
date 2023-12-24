# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program.
2.write the code appropirately.
3. check the code.
4. Run the program.

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: A.Mandhakini
RegisterNumber: 23010115
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input( )))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: A.Mandhakini
RegisterNumber: 23010115
'''
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
![lu decomposition]()
![image](https://github.com/MandhakiniA/LU-Decomposition/assets/150005194/d46445d1-6757-4b2e-b898-aefaa8556dc2)
![image](https://github.com/MandhakiniA/LU-Decomposition/assets/150005194/d5b081f5-5c1a-4df8-ba9f-9365e44eeeab)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

