# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
```
a = int(input("Enter the real part: "))
b = int(input("Enter the imaginary part: "))
x = complex(a, b)

print("Complex number:", x)
print("Real part:", x.real)
print("Imaginary part:", x.imag)
```
## Output
<img width="1202" height="225" alt="image" src="https://github.com/user-attachments/assets/e510718d-8d0c-4a9c-b20f-f7c2805201ae" />

## Result
The program was executed successfully. It reads two integers, creates a complex number using them, and prints the complex number along with its real and imaginary parts.
