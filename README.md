# Python Assignment

Submitted by:
- **Name:** Samyak Chaudhary
- **Faculty:** BCSIT 
- **Semester:** 2nd
- **College:** KFA 

## Overview
This assignment contains 20 Python programs split into two sets that demonstrate various programming concepts.

### Set A: Basic Programs
1. Calculator - Does basic math operations
2. Binary Converter - Changes numbers to binary form
3. Age Group Finder - Tells if someone is minor/adult/senior
4. Number Swapper - Swaps two numbers
5. Fibonacci Series - Shows first 10 Fibonacci numbers
6. Prime Checker - Tests if a number is prime
7. Sum Verifier - Checks if two numbers add up to third
8. Factorial Calculator - Finds factorial of a number
9. Division Program - Safely divides numbers
10. Maximum Finder - Finds biggest number in a list
11. Greeting Program - Shows name and age
12. Vowel Counter - Counts vowels in text
13. Multiplication Table - Shows times table
14. Triangle Pattern - Makes star triangle
15. Pyramid Pattern - Makes star pyramid

### Set B: LeetCode Problems
1. Palindrome Number - Checks if number reads same both ways
2. Single Number - Finds non-repeated number
3. Two Sum - Finds number pairs that add to target
4. Happy Number - Special number sequence checker
5. Duplicate Finder - Checks for repeated numbers

## How to Run
1. Open `Assignment.ipynb` in Jupyter Notebook
2. Run each cell in order
3. Enter input when asked

## Requirements
- Python 3
- Jupyter Notebook

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

9. **Safe Division**
   - Performs division of two numbers
   - Includes zero division error handling

10. **Max Finder**
    - Takes a list of numbers
    - Returns maximum value using max() function

11. **Greeter**
    - Takes name and optional age parameter
    - Demonstrates default parameter usage

12. **Vowel Counter**
    - Counts number of vowels in a given string
    - Case-insensitive counting

13. **Times Table**
    - Prints multiplication table up to 10
    - Uses f-strings for formatting

14. **Star Pattern**
    - Prints right-angled triangle using asterisks
    - Demonstrates pattern printing

15. **Pyramid**
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

5. **Duplicate Checker**
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