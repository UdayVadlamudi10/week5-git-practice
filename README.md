# Arithmetic Operations Calculator

A lightweight Python command-line utility that takes two integers from the user and computes the five basic mathematical operations in real time.

---

## Features

- **Addition:** Computes the total sum ($A + B$).
- **Subtraction:** Computes the mathematical difference ($A - B$).
- **Multiplication:** Calculates the product ($A * B$).
- **Division:** Returns the floating-point quotient ($A / B$).
- **Modulo:** Determines the remainder after division ($A % B$).

---

## Tech Stack

- **Language:** Python 3.8+
- **Libraries:** Python Standard Library (no third-party dependencies required)

---

## Installation & Setup

1. Verify your Python installation:
python --version

2. How to Run
python Arithmetic_Operations.py

3. Example Output
A: 15
B: 4
Sum =  19
Difference =  11
Product =  60
Division =  3.75
Reminder =  3

4. Limitations & Future Improvements
Current Limitations:   Inputting zero (0) for the second number (B) causes a runtime ZeroDivisionError.
Passing text or floating-point numbers triggers an unhandled ValueError.
Future Improvements:Implement try...except exception handling to gracefully manage division by zero and invalid inputs.
Add support for floating-point calculations using float(input(...)).
Add a loop (while True) allowing users to execute multiple calculations without restarting the script.