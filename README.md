# Python Assignment 3 — Loops and Functions

A beginner Python project demonstrating loop control, conditional logic, and user-defined functions through three small interactive programs.

## Project Overview

| Program | What it does | Python concepts |
|---|---|---|
| Number Guessing Game | Lets a user guess a randomly generated number from 1 to 10 | `while`, `if/elif/else`, `break`, `continue`, loop `else`, `random.randint()` |
| Multiplication Table Generator | Prints a number's multiplication table from 1 to 10 | `for`, `range()`, arithmetic, user input |
| BMI Calculator | Calculates BMI from weight in kilograms and height in meters | Functions, parameters, `return`, `float()`, formatted output |

## Skills Demonstrated

- Writing readable, beginner-friendly Python code
- Using loops and conditional statements to control program flow
- Collecting and converting user input
- Defining and calling a function with parameters and a return value
- Formatting numeric output to two decimal places

## Getting Started

### Requirements
- Python 3
- Jupyter Notebook, JupyterLab, or Google Colab

The project uses Python's built-in `random` module and does not require external packages.

### Run the notebook
1. Open **[Python Assignment 3.ipynb](./Python%20Assignment%203.ipynb)**.
2. Open it in Jupyter Notebook/JupyterLab, or upload it to Google Colab.
3. Run the cells in order.
4. Enter the values requested by each program.

## Example Results

### Number Guessing Game
The game gives feedback for guesses that are too high, too low, correct, or outside the 1–10 range. Invalid out-of-range guesses do not consume an attempt.

### Multiplication Table
For input `5`, the program prints the products from `5 x 1 = 5` through `5 x 10 = 50`.

### BMI Calculator
Example input:
- Weight: `58` kg
- Height: `1.62` m

Expected output:
```text
Your BMI is: 22.10
```

## Learning Outcomes

After completing this assignment, I practiced:
- Choosing between `while` and `for` loops
- Using `break` and `continue` to change loop execution
- Applying a `while ... else` block
- Creating a reusable function and returning a calculated result

## Repository Contents

- `Python Assignment 3.ipynb` — notebook with all three programs.
- `README.md` — project overview and run instructions.

## Future Improvements

- Add input validation for non-numeric guesses and invalid BMI measurements.
- Add automated test cases for the BMI calculation and game logic.

---

*Created as part of my Python learning journey.*
