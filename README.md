# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```python
Program to find the square root for the given number(newton's method) using function.
Developed by:Suriya prakash.S 
RegisterNumber:23013599
def sqrt():
    x=int(input())
    b=x
    for i in range(10):
        x=0.5*(x+b/x)
    return x
print("Square root of the number:",sqrt())    
```

## Output:
![image](https://github.com/arulsuriyalokeshy/Square-root-of-a-number/assets/149130151/272eff91-e23b-4f41-88e8-3ccb986db869)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
