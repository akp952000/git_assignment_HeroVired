# git_assignment_HeroVired
# CalculatorPlus

## 1.Overview

CalculatorPlus is a Python application that provides basic arithmetic operations, such as addition, subtraction, multiplication, and division. It now also includes a feature for calculating the square root of a number.

## 2.Assignment Steps

### Step a: Create a Repository
- Create a repository named `git_assignment_HeroVired` on GitHub.

### Step b: Create a `dev` Branch and Add Initial Code
#### Clone the repository and create a `dev` branch:
- git clone https://github.com/<your-username>/git_assignment_HeroVired.git<br>
- cd git_assignment_HeroVired<br>
- git checkout -b dev<br>
- git add calculator.py<br>
- git commit -m "Add basic arithmetic operations and skeleton for square root feature"<br>
- git push origin dev<br>

### Step c: Merge dev into main and Release Version 1
#### Switch to main branch and merge dev:
- git checkout main<br>
- git merge dev<br>
- git push origin main<br>
#### Create a release for version 1 on GitHub
- Navigate to the releases page on GitHub and create a new release with tag v1.0.
### Step d: Add Classmates as Collaborators
#### Navigate to the repository settings:
- Go to the "Settings" tab of your repository.
#### Add collaborators:
- Click "Collaborators & teams" in the sidebar.<br>
- Invite classmates by entering their GitHub username or email and sending the invitation.<br>
### Step e: Implement the Square Root Feature
#### Create a new branch feature/sqrt:
- git checkout -b feature/sqrt<br>
#### Implement the square root function in calculator.py:
```
def square_root(self, x):
return math.sqrt(x)
```
#### Commit and push the changes:
- git add calculator.py<br>
- git commit -m "Implement square root feature"<br>
- git push origin feature/sqrt<br>
### Step f: Fix a Critical Bug
#### Fix the bug in calculator.py:
```
def divide(self, a, b):
    if b == 0:
        raise ValueError("Cannot divide by zero.")
    return a / b
```
#### Commit and push the changes, and merge them into dev and main:
- git add calculator.py<br>
- git checkout dev<br>
- git push origin dev<br>
- git checkout main<br>
- git merge dev<br>
- git push origin main
### Step g: Keep feature/sqrt Branch Up-to-Date
#### Switch back to feature/sqrt and rebase onto dev:
- git checkout feature/sqrt
### Step h: Create a Pull Request
- Create a pull request targeting the main branch and request a code review.
### Step i: Address Review Feedback
- Make any necessary changes based on the review feedback, and push the updates.
### Step j: Merge feature/sqrt into dev and Test
#### Merge the feature/sqrt branch into dev and test the application:
- git checkout dev<br>
- git merge feature/sqrt<br>
- git push origin dev<br>
### Step k: Finalize and Create Version 2 Release
#### Merge dev into main and create a version 2 release on GitHub:
- git checkout main<br>
- git merge dev<br>
- git push origin main<br>
- Create a new release with tag v2.0 on GitHub.<br>
## 3.Conclusion
The CalculatorPlus application now includes the new square root feature and has addressed the critical bug in the divide function. The version 2 release is now available.

# geometry-calculator
## 1.Create a New Branch
**Create a new branch named feature/circle-area to work on the circle area feature:**
- git checkout -b feature/circle-area
## 2.Stash Changes for Circle Area Feature
**Before committing the changes, stash them to save the incomplete feature implementation:**
- git stash
## 3.Verify that the working directory is clean
- git status
## 4.Create a New Branch for Rectangle Area Feature
**Create a new branch named feature/rectangle-area to work on the rectangle area feature:**
- git checkout -b feature/rectangle-area
## 5.Stash Changes for Rectangle Area Feature
**Before committing the changes, stash them to save the incomplete feature implementation:**
- git stash
## 6.Verify that the working directory is clean
- git status
## 7.Switch Back to Circle Area Branch
**Switch back to the feature/circle-area branch to continue working on the circle area feature:**
- git checkout feature/circle-area
## 8.Retrieve the stashed changes
- git stash pop
## 9.Commit and Push Circle Area Feature
**Commit and push the changes to the feature/circle-area branch**
- git add .<br>
- git commit -m "Complete circle area feature"<br>
- git push origin feature/circle-area<br>
## 10.Switch Back to Rectangle Area Branch
**Switch back to the feature/rectangle-area branch to continue working on the rectangle area feature**
- git checkout feature/rectangle-area
## 11.Retrieve the stashed changes:
- git stash pop
## 12.Commit and Push Rectangle Area Feature
**Commit and push the changes to the feature/rectangle-area branch**
- git add .<br>
- git commit -m "Complete rectangle area feature"<br>
- git push origin feature/rectangle-area<br>
## 13.Create Pull Requests
- Create pull requests to the dev branch for both features.
## 14.Review and Merge
- Have another team member or reviewer review your pull requests. After receiving approval, merge both pull requests into the dev branch.
