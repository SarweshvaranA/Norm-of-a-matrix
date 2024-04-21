# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 1-norm ,2-norm ,Infinity norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
'''
Program to find 1-Norm of matrix
Developed by : SARWESHVARAN A
Register Number:212223230198
'''
import numpy as np 
matrix=eval(input())
Result=np.linalg.norm(matrix,1)
print("{:.2f}".format(Result))




'''
Program to find 2-norm of a matrix.
Developed by:SARWESHVARAN A
RegisterNumber: 212223230198
'''
import numpy as np
matrix=eval(input())
Result=np.linalg.norm(matrix,2)
print("{:.2f}".format(Result))




'''
Program to find Infinity Norm of a matrix
Developed by : SARWESHVARAN A
Register Number:212223230198
'''
import numpy as np
matrix=eval(input())
Result=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(Result))





```
## Output:
## 1-Norm of a matrix
![1-Norm of matrix](<1-norm of matrix.png>)

## 2-Norm of a matrix 
![2-Norm of matrix](<2-norm of matrix.png>)

## Infinity of a matrix
![Infinity of matrix](<Infinity of matrix.png>)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
