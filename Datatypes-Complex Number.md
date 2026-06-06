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

# Creating a complex number
x = complex(a, b)

# Displaying the complex number and its parts
print("Complex Number:", x)
print("Real Part:", x.real)
print("Imaginary Part:", x.imag)
```

## Output

<img width="398" height="392" alt="image" src="https://github.com/user-attachments/assets/ae362415-0537-4fb7-bdb0-cc83f3d320e8" />

## Result
The Python program to create and display a complex number along with its real and imaginary components was successfully written, executed, and verified.
