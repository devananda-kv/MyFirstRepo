# MyFirstRepo
# Largest Number Finder (Python)

This is a simple Python program that asks the user to enter three numbers and then displays the largest among them.  
It is a beginner-friendly example demonstrating basic input, comparison, and the use of Python's built-in `max()` function.

---

##  How It Works
1. The program takes three numbers as input from the user.  
2. It uses the `max(a, b, c)` function to determine the largest number.  
3. It prints the result.

---

##  Code Example

```python
a = float(input("Enter first number: "))
b = float(input("Enter second number: "))
c = float(input("Enter third number: "))

largest = max(a, b, c)

print("The largest number is:", largest)

