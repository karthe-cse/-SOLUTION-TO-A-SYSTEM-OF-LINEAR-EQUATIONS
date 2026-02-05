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
#Developed by: Kartheeshwar D J
#RegisterNumber:212225040173
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B=np.array([-9,4,-1])
x=np.linalg.solve(A,B)
print(x)
```
## Output:

<img width="1319" height="199" alt="Screenshot 2026-02-05 133851" src="https://github.com/user-attachments/assets/6e6e1af3-5043-4986-bf6e-e69adecbe89d" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

