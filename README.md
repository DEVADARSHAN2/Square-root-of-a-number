# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1.Hardware – PCs

2.Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define a function.

2.Assign number_iters = 100 in the function to perform 100 iteratios.

3.Set i = 0.

4.Calculate  number = 0.5 * (number + a / number) for 100 iterations.

5.Return number

## Program:
```

Program to find the square root for the given number(newton's method) using function.
Developed by: DEVADARSHAN A S 
RegisterNumber : 212222110007  

```
```Python
def newton_method(number,number_iters = 100):
    a=float(number)
    for i in range(number_iters):
        number = 0.5 * (number + a / number)
    return number
a=int(input())
print("Square root of the number:",newton_method(a))
    
```    

## Output:
![image](https://github.com/DEVADARSHAN2/Square-root-of-a-number/assets/119432150/87226f2c-2df0-4e1e-a091-e81fe31e2aa0)
## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
