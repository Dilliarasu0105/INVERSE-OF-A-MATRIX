# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy as np
### Step 2: 
Assign in np.array() in inverse of matrix
### Step 3: 
Using the np.linalg.matrix_rank(),we can find the inverse of given matrix
### Step 4: 
Print the value and end the program
## Program:
```python
#Program to find the inverse of a matrix.
#Developed by: Ragavendran A
#RegisterNumber: 22008885
import numpy as np
A = np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
B = np.linalg.inv(A)
print(B)
```
## Output:
![output](/output1.png)
## Result:
Thus the inverse of given matrix is successfully solved using python program

