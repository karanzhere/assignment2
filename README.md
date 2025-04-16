# assignment2
# Python Scripts Documentation

## Overview

This repository contains two Python scripts: `Task1.py` and `Task2.py`. Each script performs a specific task as described below.

## Task1.py

### Description

`Task1.py` is a simple Python script that checks whether a given number is even or odd.

### Usage

1. Run the script.
2. Enter a number when prompted.
3. The script will display whether the entered number is even or odd.

### Code

```python
# Task 1: Check if a Number is Even or Odd
nums = int(input("Enter a number: "))
num_check = nums % 2
if num_check == 0:
    print("It's an Even Number")
else:
    print("It's an Odd number")
