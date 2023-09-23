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
```
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: M UDHAYA SANKARAN 
RegisterNumber: 212222110051
*/

def sp(num,num_iters=100):
    a=float(num)
    for i in range(num_iters):
        num=0.5*(num+a/num)
    return num
a=int(input())
print("Square root of the number:",sp(a))
```

## Output:
![image](https://github.com/Udhayasankaran04/Square-root-of-a-number/assets/119393933/f01473e2-b82d-4597-bfcd-25c1b3aa8940)
## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
