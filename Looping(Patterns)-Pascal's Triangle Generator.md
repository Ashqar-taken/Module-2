# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

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

---

## 🧪 Program
Add Code Here
```
import math
rows = int(input("Enter the number of rows: "))
c = lambda n,k : math.factorial(n) // (math.factorial(k)*math.factorial(n-k))

for n in range(rows):
    print(" "*(rows-n),end="")
    for k in range(n +1):
        value = c(n,k)
        print(f"{value} ",end="")
    print()
```
## Sample Output
![Screenshot 2025-05-22 110202](https://github.com/user-attachments/assets/7126133d-cd06-43ab-91d9-e4d54f7b0b1b)

## Result
A Python program that generates **Pascal's Triangle** using the number of rows that is accepted by the users is written successfully.
