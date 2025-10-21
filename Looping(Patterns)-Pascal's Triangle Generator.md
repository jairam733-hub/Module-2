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
a=int(input())
for i in range(0,a+1):
    for s in range(a-i-1):
        print(" ",end="")
    for j in range(i+1):
        print(math.comb(i,j),end=" ")
    
    print()
```

## Sample Output
<img width="1920" height="1080" alt="Screenshot (124)" src="https://github.com/user-attachments/assets/18ffe9aa-9260-4480-972b-c0196df40a2d" />

## Result

