# Python Programming Assignment

This repository contains a collection of Python programming exercises divided into two sets (Set A and Set B). The exercises cover various programming concepts from basic calculations to algorithm implementations.

## File Structure

```
.
├── Assignment.ipynb    # Main Jupyter notebook containing all exercises
├── factorial_module.py # Custom module for factorial calculation
└── README.md          # This documentation file
```

## Set A: Basic Programming Exercises

1. **Basic Calculator**
   - Implements a simple calculator performing addition, subtraction, multiplication, and division
   - Handles division by zero case

2. **Decimal to Binary Converter**
   - Converts decimal numbers to their binary equivalent
   - Uses Python's built-in bin() function

3. **Age Category Classifier**
   - Takes age as input
   - Classifies person as minor (<18), adult (18-59), or senior (≥60)

4. **Variable Swap**
   - Swaps values of two variables without using a third variable
   - Uses Python's tuple unpacking

5. **Fibonacci Series**
   - Prints first 10 numbers of the Fibonacci series
   - Uses efficient variable swapping technique

6. **Prime Number Checker**
   - Checks if a given number is prime
   - Implements basic prime number algorithm

7. **Sum Checker**
   - Takes three numbers as input
   - Checks if third number equals sum of first two

8. **Factorial Calculator**
   - Uses custom module (factorial_module.py)
   - Calculates factorial of a given number

9. **Division Handler**
   - Performs division of two numbers
   - Includes zero division error handling

10. **Maximum Number Finder**
    - Takes a list of numbers
    - Returns maximum value using max() function

11. **Greeting Function**
    - Takes name and optional age parameter
    - Demonstrates default parameter usage

12. **Vowel Counter**
    - Counts number of vowels in a given string
    - Case-insensitive counting

13. **Multiplication Table**
    - Prints multiplication table up to 10
    - Uses f-strings for formatting

14. **Right Triangle Pattern**
    - Prints right-angled triangle using asterisks
    - Demonstrates pattern printing

15. **Pyramid Pattern**
    - Prints pyramid pattern using asterisks
    - Shows advanced pattern printing

## Set B: LeetCode Problem Solutions

1. **Palindrome Number**
   - Checks if a number is palindrome
   - LeetCode problem implementation

2. **Single Number**
   - Finds non-duplicate number in array
   - Uses XOR operation for efficient solution

3. **Two Sum**
   - Finds two numbers that add up to target
   - Basic implementation with nested loops

4. **Happy Number**
   - Determines if a number is "happy"
   - Uses set to detect cycles

5. **Contains Duplicate**
   - Checks for duplicates in array
   - Uses set comparison for efficiency

## Custom Modules

### factorial_module.py
```python
def factorial(n):
    result = 1
    for i in range(1, n + 1):
        result *= i
    return result
```
- Custom module for factorial calculation
- Used in exercise 8 of Set A

## Usage

1. Make sure you have Python and Jupyter Notebook installed
2. Open `Assignment.ipynb` in Jupyter Notebook
3. Run cells sequentially to see the output
4. Input values when prompted

## Requirements

- Python 3.x
- Jupyter Notebook
- Basic Python packages (all built-in) 