# Project Documentation: Python Loops and Functions

## 1. Project Summary

This project contains three small interactive Python programs created to practice foundational programming skills:

1. Number Guessing Game
2. Multiplication Table Generator
3. BMI Calculator

The project is intended as a learning exercise. It demonstrates basic control flow and function usage; it is not a production application or a data-analysis project.

## 2. Objectives

- Use a `while` loop to repeat an action until a condition is met.
- Use `for` and `range()` to iterate through a sequence of numbers.
- Apply conditional statements to make decisions.
- Demonstrate `break` and `continue` in a loop.
- Define a function with parameters and a return value.
- Accept keyboard input and convert it to numeric values.

## 3. Program Details

### Number Guessing Game

**Input:** A whole-number guess from 1 to 10.

**Process:**
- Python generates a secret number with `random.randint(1, 10)`.
- The player gets up to three valid guesses.
- Guesses outside 1–10 display a message and do not use an attempt.
- Valid guesses receive a “too high”, “too low”, or correct-answer message.
- `break` ends the loop after a correct guess, while the loop's `else` displays a message if attempts run out.

**Concepts:** `random`, `while`, `if/elif/else`, `continue`, `break`.

### Multiplication Table Generator

**Input:** A whole number.

**Process:** A `for` loop with `range(1, 11)` multiplies the input number by each integer from 1 through 10 and prints the result.

**Concepts:** `input()`, `int()`, `for`, `range()`, arithmetic, printing.

### BMI Calculator

**Input:** Weight in kilograms and height in meters.

**Formula:** BMI = weight (kg) / height (m)²

**Process:** The `calculate_bmi(weight, height)` function calculates and returns the BMI. The result is displayed to two decimal places.

**Concepts:** functions, parameters, `return`, `float()`, arithmetic, f-strings.

**Scope note:** This exercise demonstrates the calculation only. BMI is a screening measure and this simple program does not provide medical advice or interpret BMI categories.

## 4. How to Run

1. Open `Python Assignment 3.ipynb` using Jupyter Notebook, JupyterLab, or Google Colab.
2. Run the cells from top to bottom.
3. Enter the requested values when prompted.
4. For the guessing game, enter a number from 1 to 10 to use a valid attempt.

Python 3 is required. The programs use Python's standard library and need no third-party packages.

## 5. Manual Test Checklist

| Program | Test input / action | Expected behavior |
|---|---|---|
| Number Guessing Game | Guess below the secret number | Displays “Too low. Try again.” |
| Number Guessing Game | Guess above the secret number | Displays “Too high. Try again.” |
| Number Guessing Game | Enter 0 or 15 | Displays the out-of-range message; attempt count is unchanged |
| Number Guessing Game | Guess the secret number | Congratulates the player and ends the loop |
| Multiplication Table | Enter 5 | Prints the table from 5 × 1 through 5 × 10 |
| BMI Calculator | Enter weight 58 and height 1.62 | Displays BMI as 22.10 |

The guessing game generates a random secret number, so its exact sequence of feedback varies between runs.

## 6. Current Limitations and Possible Improvements

- The programs expect valid numeric input; non-numeric entries may raise a conversion error.
- The BMI calculator expects a positive height in meters.
- The guessing game uses a fixed range and a fixed number of valid attempts.

Possible future enhancements include input validation, configurable game difficulty, automated tests, and a small data-analysis project using Pandas. These are future ideas, not features currently implemented.

## 7. Skills Demonstrated

- Python fundamentals and problem solving
- Loops and conditional logic
- Functions and return values
- User input and type conversion
- Basic manual test planning
- Technical documentation

---
