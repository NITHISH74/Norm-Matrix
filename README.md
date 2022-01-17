# 2-Norm of a matrix
## Aim
To write a program to find the 2-norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()
	2. The 2-Norm of a matrix is given by 
![norm](./normeqn1.jpg)
    
    3. Find the 2-norm of the matrix using np.linalg.norm()
	4. Print the norm of the matrix in two decimal places.
## Program:
```
'''
Program to find 2-norm of a matrix.
Developed by: NITHISHWAR S
RegisterNumber: 21002766
'''
import numpy as np

n=eval(input())
val=np.linalg.norm(n,2)
print('{:.2f}'.format(val))
# Type your code here


```
## Input and Output:
![image](https://user-images.githubusercontent.com/94164665/149737647-0261e731-07a6-4cc7-823f-be13f800a537.png)


## Result
Thus the program for 2-norm of a matrix is written and verified.
