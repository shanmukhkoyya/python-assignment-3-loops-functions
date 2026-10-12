# Python Fundamentals: Loops, Control Flow & Functions

A beginner Python project demonstrating core programming concepts through three small interactive programs. This repository is a learning project and a foundation for more advanced Python and data-analysis work.

## Programs

### 1. Number Guessing Game
- Generates a random integer from 1 to 10.
- Allows up to three valid guesses.
- Gives feedback when a guess is too high, too low, correct, or outside the valid range.
- Demonstrates `while`, `if/elif/else`, `continue`, `break`, and `while ... else`.

### 2. Multiplication Table Generator
- Accepts a number from the user.
- Uses `for` and `range(1, 11)` to print its multiplication table from 1 to 10.

### 3. BMI Calculator
- Defines a reusable `calculate_bmi(weight, height)` function.
- Calculates BMI with `weight / (height ** 2)`.
- Accepts weight in kilograms and height in meters.
- Displays the result to two decimal places.

## Skills Demonstrated

- Python loops and conditional logic
- `break`, `continue`, and `range()`
- Functions, parameters, and return values
- User input and type conversion
- Arithmetic and formatted output
- Basic manual test planning

## Getting Started

**Requirements:** Python 3 and Jupyter Notebook, JupyterLab, or Google Colab. No third-party packages are required.

1. Open [Python Assignment 3.ipynb](./Python%20Assignment%203.ipynb).
2. Run the notebook cells in order.
3. Enter the values requested by each program.

## Documentation

- [Project Documentation](./PROJECT_DOCUMENTATION.md) — program logic, learning objectives, manual test checklist, limitations, and possible future improvements.

## Example Results

- **Multiplication table:** entering `5` prints results from `5 x 1 = 5` through `5 x 10 = 50`.
- **BMI calculator:** entering `58` kg and `1.62` m displays `Your BMI is: 22.10`.
- **Number guessing game:** provides feedback for each guess; the secret number changes each run.

## Repository Contents

| File | Description |
|---|---|
| `Python Assignment 3.ipynb` | Notebook containing all three exercises |
| `PROJECT_DOCUMENTATION.md` | Detailed project documentation and manual test checklist |

## Learning Outcome

This assignment helped me practice Python fundamentals and problem solving using loops, conditional statements, and functions. The project is intentionally beginner-level; input validation and automated tests are possible next improvements.

---
*Part of my ongoing Python and data analytics learning journey.*
