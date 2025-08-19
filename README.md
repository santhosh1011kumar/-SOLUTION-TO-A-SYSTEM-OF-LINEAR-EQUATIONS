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
#Developed by: Santhosh kumar A
#RegisterNumber:212224230250


import numpy as np
A=np.array([[1,-3],[3,1]])
B=np.array([0,10])
C=np.linalg.solve(A,B)
print(C)
```

## Output:
<img width="943" height="910" alt="Screenshot 2025-08-19 144033" src="https://github.com/user-attachments/assets/acf2addc-47ae-4b69-a959-9193c7e296b2" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

