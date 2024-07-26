# git_assignment_HeroVired
# CalculatorPlus

## Overview

CalculatorPlus is a Python application that provides basic arithmetic operations, such as addition, subtraction, multiplication, and division. It now also includes a feature for calculating the square root of a number.

## Assignment Steps

### Step a: Create a Repository
**Create a repository named `git_assignment_HeroVired` on GitHub.**

### Step b: Create a `dev` Branch and Add Initial Code
**Clone the repository and create a `dev` branch:**
git clone https://github.com/<your-username>/git_assignment_HeroVired.git
cd git_assignment_HeroVired
git checkout -b dev
git add calculator.py
git commit -m "Add basic arithmetic operations and skeleton for square root feature"
git push origin dev

### Step c: Merge dev into main and Release Version 1
Switch to main branch and merge dev:
git checkout main
git merge dev
git push origin main
**Create a release for version 1 on GitHub:**
Navigate to the releases page on GitHub and create a new release with tag v1.0.
### Step d: Implement the Square Root Feature
**Create a new branch feature/sqrt:**
git checkout -b feature/sqrt
**Implement the square root function in calculator.py:**
def square_root(self, x):
return math.sqrt(x)
**Commit and push the changes:**
git add calculator.py
git commit -m "Implement square root feature"
git push origin feature/sqrt
### Step e: Fix a Critical Bug
**Fix the bug in calculator.py:**
def divide(self, a, b):
    if b == 0:
        raise ValueError("Cannot divide by zero.")
    return a / b
**Commit and push the changes, and merge them into dev and main:**
git add calculator.py
git checkout dev
git push origin dev
git checkout main
git merge dev
git push origin main
### Step f: Keep feature/sqrt Branch Up-to-Date
**Switch back to feature/sqrt and rebase onto dev:**
git checkout feature/sqrt


