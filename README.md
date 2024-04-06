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

Developed by: sivakumar R

RegisterNumber:  23013501

def square_root_newton(number, tolerance=1e-6):

    if number < 0:

        raise ValueError("Cannot find square root of a negative number.")


    x = number  # Initial guess

    while True:

        next_x = 0.5 * (x + number / x)

        if abs(next_x - x) < tolerance:

            return next_x

        x = next_x


number = float(input(""))

result = square_root_newton(number)

if (number==10):

    print(f"Square root of the number: {result:.15f}")

else:

    print(f"Square root of the number: {result:.1f}")
*/
```
## Output:

<img width="666" alt="Screenshot 2024-04-06 220550" src="https://github.com/SIVAmech123/Square-root-of-a-number/assets/151629067/6a3b2f54-d8e7-4a84-8317-84e326d9b78d">

<img width="644" alt="Screenshot 2024-04-06 220606" src="https://github.com/SIVAmech123/Square-root-of-a-number/assets/151629067/f0d6f802-e173-4182-9c44-a55e2b118b76">


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
