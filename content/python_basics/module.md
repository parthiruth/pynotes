---
title: Module
date: 2026-04-19
author: Your Name
cell_count: 1
score: 0
---

```python
#1 Create a Python module that contains a function to print a greeting message and import it into another program.
def function_call_name(name):
    print("hello " + name)

#2 Create a module that contains a function to calculate the square of a number, and use it in another file.
def check_square():
    check_number= int(input("2. Enter a square number:"))
    print(check_number ** 2)

#3 Write a Python program that imports the math module and calculates the square root of a number.
def calculate_squarerroot():
    check_number= int(input("3. Enter a SQ root Number:"))
    print(check_number ** 0.5)

#4 Write a Python program that imports the math module and calculates the power of a number.
def power_of_number():
    num, power = map(int, input("4. Enter two number with space one is  num && one is power : ").split(" "))
    print(num ** power)

#5  Create a custom module that contains two functions: one to add numbers, one to subtract numbers, Import and use both functions. 
#6  Write a Python program that imports a module using from module import function syntax.
def add_and_sub():
    num1, num2 = map(int, input("6. Enter two number with space for addition and subtraction :").split())
    print(f"addition of 2 number is : {num1 + num2}\n Substract of 2 number is : {num1 - num2}")

#7  Create a module with a function that checks whether a number is even or odd, then import it into another program.
def even_or_odd():
    result= int(input("7. Enter a number to find even or odd:"))
    if result % 2 == 0:
        print("Even")
    else:
        print("Odd")

#8 Write a Python program that imports the random module and prints a random number.
# Done
#9 Write a Python program that imports the datetime module and prints the current date.
# Done

# 10 Create a custom module that contains a function to reverse a string, and import it into another file.
def reverse_string():
    name = input("10. enter a name: ")
    print(name[::-1])





```


---
**Score: 0**