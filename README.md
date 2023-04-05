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
```python program
#Program to find the solution for the given linear equations.
#Developed by: E.Nandhini
#RegisterNumber:212222100030
import numpy as no
A=no.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B=no.array([-9,4,-1])
result=no.linalg.solve(A,B)
print(result)
```
## Output:
![linear equations](https://user-images.githubusercontent.com/121998147/229991538-6971d0a0-93d0-4f4e-b1b5-2b57b6f291b7.png)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

