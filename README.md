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
## Program
```py
#Program to find the solution for the given linear equations.
#Developed by: SUROTHAAMAN R
#RegisterNumber:23008504
import numpy as np
a=np.array([[1,3],[2,5]])
b=np.array([5,-3])
soln=np.linalg.solve(a,b)
print(soln)
````
## Output:
![Screenshot (28)](https://github.com/surothaaman/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/133313653/c954d09a-4c61-47bc-97a9-5f7f5df5d541)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

