# EX-03-INVERSE-OF-A-MATRIX
## DATE:
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the inverse of the given matrix
### Step 4: 
End the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: G Leka Sri 
#RegisterNumber: 212223100025
import numpy as np
a=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
ans=np.linalg.inv(a)
print(ans)
```
## Output:
![Screenshot 2024-09-04 161727](https://github.com/user-attachments/assets/dad549f8-0208-4491-83b8-99b9ee31cf9d)

## Result:
Thus the inverse of given matrix is successfully solved using python program

