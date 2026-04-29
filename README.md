# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: srinikesh t
#RegisterNumber:212225040427
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrixA= np.array([[5, -3,-10],[2,2,-3],[-3,-1,5]])
const=np.array([-9,4,-1])
result=np.linalg.solve(matrixA, const)
print(result)
```
## Output:
<img width="401" height="158" alt="image" src="https://github.com/user-attachments/assets/ba6ad14a-f6b8-4a3c-bbb1-6b3335f4d6e6" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

