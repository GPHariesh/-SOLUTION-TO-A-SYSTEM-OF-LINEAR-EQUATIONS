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
import numpy as hp
A=hp.array([[1,3],[2,5]])
B=hp.array([5,-3])
result=hp.linalg.solve(A,B)
print(result)
```

## Output:
![Screenshot (88)](https://github.com/user-attachments/assets/a3d1dce6-672b-43ad-bec8-72599acaa0a7)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

