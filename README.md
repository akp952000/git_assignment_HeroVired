# git_assignment_HeroVired
# CalculatorPlus

## Overview

CalculatorPlus is a Python application that provides basic arithmetic operations, such as addition, subtraction, multiplication, and division. It now also includes a feature for calculating the square root of a number.

## Assignment Steps

### Step a: Create a Repository
Create a repository named `git_assignment_HeroVired` on GitHub.

### Step b: Create a `dev` Branch and Add Initial Code
#### Clone the repository and create a `dev` branch:
git clone https://github.com/<your-username>/git_assignment_HeroVired.git<br>
cd git_assignment_HeroVired
git checkout -b dev
git add calculator.py
git commit -m "Add basic arithmetic operations and skeleton for square root feature"
git push origin dev

### Step c: Merge dev into main and Release Version 1
#### Switch to main branch and merge dev:
*git checkout main
*git merge dev
*git push origin main
#### Create a release for version 1 on GitHub
*Navigate to the releases page on GitHub and create a new release with tag v1.0.
### Step d: Add Classmates as Collaborators
#### Navigate to the repository settings:
*Go to the "Settings" tab of your repository.
#### Add collaborators:
*Click "Collaborators & teams" in the sidebar.
*Invite classmates by entering their GitHub username or email and sending the invitation.
### Step e: Implement the Square Root Feature
#### Create a new branch feature/sqrt:
*git checkout -b feature/sqrt
#### Implement the square root function in calculator.py:
*def square_root(self, x):
*return math.sqrt(x)
#### Commit and push the changes:
*git add calculator.py
*git commit -m "Implement square root feature"
*git push origin feature/sqrt
### Step f: Fix a Critical Bug
#### Fix the bug in calculator.py:
def divide(self, a, b):
    if b == 0:
        raise ValueError("Cannot divide by zero.")
    return a / b
#### Commit and push the changes, and merge them into dev and main:
*git add calculator.py
*git checkout dev
*git push origin dev
*git checkout main
*git merge dev
*git push origin main
### Step g: Keep feature/sqrt Branch Up-to-Date
#### Switch back to feature/sqrt and rebase onto dev:
*git checkout feature/sqrt
### Step h: Create a Pull Request
*Create a pull request targeting the main branch and request a code review.
### Step i: Address Review Feedback
*Make any necessary changes based on the review feedback, and push the updates.
### Step j: Merge feature/sqrt into dev and Test
#### Merge the feature/sqrt branch into dev and test the application:
*git checkout dev
*git merge feature/sqrt
*git push origin dev
### Step k: Finalize and Create Version 2 Release
#### Merge dev into main and create a version 2 release on GitHub:
*git checkout main
*git merge dev
*git push origin main
*Create a new release with tag v2.0 on GitHub.
### Conclusion
The CalculatorPlus application now includes the new square root feature and has addressed the critical bug in the divide function. The version 2 release is now available.

