# Student Grade Calculator

A simple Python application that calculates the average grade of a student and determines whether the student passes.

## Installation

Install the project dependencies:

```bash
pip install -r requirements.txt
```

## Run Tests

Execute the automated tests using pytest:

```bash
pytest -v
```

## Run Linting

Check the code quality using flake8:

```bash
flake8 .
```

## Usage

Import the calculator functions into your Python code:

```python
from calculator import calculate_average, is_passing, get_grade_category

grades = [12, 15, 17]

average = calculate_average(grades)

print("Average:", average)
print("Passing:", is_passing(average))
print("Category:", get_grade_category(average))
```

## Grade Categories

| Average | Category |
|---|---|
| 16 or higher | Excellent |
| 12 to 15.99 | Good |
| 10 to 11.99 | Average |
| Below 10 | Fail |

## Technologies

- Python 3.11
- pytest
- flake8
- GitHub Actions
