# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

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

