## Python Programming Module 2
## Name: Antony Aswin Kumar L
## Register Number : 212225040024

## Ex:1  Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program :

```
a = 16

b=bin(a)

print(f"Binary value of {a} is {b}")
```

## Output:

<img width="423" height="174" alt="image" src="https://github.com/user-attachments/assets/9f426aa0-9b1c-4012-ba69-6f806a3f8aa4" />

## Result
Thus the Python program to convert the number **16** into its **binary representation** using built-in Python functions is executed successfully.


## EX:2  Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program:

```
def func(a,b):
    mod_oper = a%b
    return mod_oper

a=int(input("Enter the First number: "))
b=int(input("Enter the Second number: "))

print(f"The Result of {a} % {b} =",func(a,b))
```

## Output:

<img width="600" height="279" alt="image" src="https://github.com/user-attachments/assets/2a5b9d06-4b2c-445f-b40e-f5f90f9cca78" />


## Result:

Thus the Python program that defines a function which accepts two values and returns their **modulo** using the '%' operator is executed successfully.


## EX:3  Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program:

```
a = int(input("Enter a number : "))
b = int(input("Enter a number : "))

func=lambda x,y:x+y

print("Sum is:",func(a,b))
```

## Output:

<img width="495" height="226" alt="image" src="https://github.com/user-attachments/assets/6eb51c7e-28a4-4c09-90e2-748e96efda38" />

## Result:
Thus the Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum is executed successfully.



## Ex:4  Looping(Patterns)-Pascal's Triangle Generator in Python

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

## 🧪 Program:

```
def fact(n): 
    if n == 0 or n == 1: 
        return 1 
    else: 
        return n * fact(n - 1)

rows = int(input("Enter number of rows: "))

for n in range(rows): 
    print(" " * (rows - n), end="")
    for k in range(n + 1):
        value = fact(n) // (fact(k) * fact(n - k))
        print(value, end=" ")
    print()
```

## Output

<img width="625" height="537" alt="image" src="https://github.com/user-attachments/assets/63400077-7696-4bf5-a515-d7116ee30a4a" />

## Result:
Thus the To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.
