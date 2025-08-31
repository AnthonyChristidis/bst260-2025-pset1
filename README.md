# Problem Set 1: Unix, Quarto, and RStudio Projects

## Overview

This assignment introduces you to RStudio projects, Quarto documents, Unix commands, and file organization. You'll work with quadratic equations, create plots, and practice using command-line tools.

## Getting Started

1.  **Accept the assignment** via the GitHub Classroom link
2.  **Clone this repository** to your local machine
3.  **Open the repository folder** in RStudio as a project
4.  **Complete all problems** in the `pset-01-unix-quarto.qmd` file

## Assignment Files

-   `pset-01-unix-quarto.qmd` - Main assignment file with all problems
-   `README.md` - This instruction file

## What You'll Create

By the end of this assignment, your repository should contain:

**Root Directory:**

-   `pset-01-unix-quarto.qmd` - Main assignment file
-   `beginning.qmd` - Created in Problem 1

**Directories to Create:**

-   `img/`
    -   `screenshot.png` - Your RStudio screenshot (Problem 2)
-   `docs/`
    -   `beginning.pdf` - Rendered PDF (Problem 5)
-   `data/`
    -   `coefs.txt` - Coefficient file (Problem 7)
-   `code/`
    -   `quadratic.qmd` - Copy of beginning.qmd (Problem 8)

## Instructions

1.  **Work through each problem** in order in the `pset-01-unix-quarto.qmd` file
2.  **Follow the naming conventions** specified in each problem
3.  **Include all commands** you use in the designated code blocks
4.  **Test that your files render** before submitting

## Technical Requirements

-   Use **relative paths** when reading files (unless specifically asked for absolute paths)
-   Include **all Unix commands** you use
-   Make sure your **Quarto documents render** without errors
-   Take **screenshots** as requested

## Submission

Your submission is your final committed and pushed repository. Make sure to:

1.  **Complete all problems** in the assignment file
2.  **Commit your changes** frequently with meaningful messages
3.  **Push your final work** to GitHub
4.  **Verify** that all files are visible in your GitHub repository

## Due Date

**September 10, 2025**

## Getting Help

-   Post questions on our class Slack
-   Attend office hours
-   Check the course website for additional resources

## Tips

-   Start early and work incrementally
-   Test your code as you go
-   Use descriptive commit messages
-   Ask for help if you get stuck with Unix commands

## Grading

| **Criteria** | **Excellent (A)** | **Good (B)** | **Satisfactory (C)** | **Needs Improvement (D-F)** |
|:-------------|:------------------|:-------------|:---------------------|:---------------------------|
| **File Organization & Structure (25 points)** | 23-25: Perfect directory structure with all required folders (`img`, `docs`, `data`, `code`) in correct locations. Files properly named and placed. | 20-22: Correct structure with minor placement issues. Most files in right locations. | 15-19: Basic structure present but some directories missing or files misplaced. | 0-14: Poor organization, missing directories, files in wrong locations. |
| **Unix Commands & Terminal Skills (20 points)** | 18-20: All Unix commands shown and correct (`mkdir`, text editor commands, `cp`). Demonstrates clear understanding of command line. | 16-17: Most commands shown correctly with minor syntax issues. | 12-15: Some Unix commands shown but missing several or incorrect syntax. | 0-11: Few or no Unix commands shown, major errors in command usage. |
| **Quarto Document Creation & Rendering (20 points)** | 18-20: Both `beginning.qmd` and `quadratic.qmd` render perfectly. PDF in correct location. Clean formatting and structure. | 16-17: Documents render with minor formatting issues. PDF created successfully. | 12-15: Documents render but with some formatting problems or rendering issues. | 0-11: Documents don't render, major Quarto syntax errors, or missing PDF. |
| **R Programming & Mathematical Calculations (15 points)** | 14-15: Quadratic formula implemented correctly, handles real solutions properly, excludes complex numbers. Code is clean and efficient. | 12-13: Correct mathematical implementation with minor coding style issues. | 9-11: Basic implementation works but with some logical or coding errors. | 0-8: Incorrect mathematical implementation, major coding errors, or doesn't work. |
| **Data Visualization & File I/O (10 points)** | 9-10: Plot displays correctly, reads coefficients from file successfully, demonstrates understanding of relative vs absolute paths. | 8: Plot and file reading work with minor issues. Shows path understanding. | 6-7: Basic plotting and file reading implemented but with some issues. | 0-5: Plot missing/incorrect, file reading doesn't work, or major path understanding problems. |
| **Documentation & Code Comments (5 points)** | 5: Excellent documentation, clear explanations of process, code well-commented, screenshot included properly. | 4: Good documentation with minor gaps, screenshot included. | 3: Basic documentation present, some explanations missing. | 0-2: Poor documentation, missing explanations, screenshot missing or poorly integrated. |
| **Technical Requirements & Submission (5 points)** | 5: All files committed and pushed correctly, repository structure visible on GitHub, follows naming conventions perfectly. | 4: Properly submitted with minor naming convention issues. | 3: Submitted but with some technical issues or naming problems. | 0-2: Poor submission, files missing from GitHub, major technical problems. |

## Key Assessment Points

**Specific Things Graders Will Look For:**

1. **Commands shown**: Students must include the actual Unix commands they used
2. **Directory structure**: Exact folder names and placement as specified
3. **File paths**: Understanding of relative vs absolute paths (Problem 10)
4. **Screenshot**: Properly embedded in Quarto document
5. **Rendering success**: Both Quarto documents must render to PDF
6. **Real solutions only**: Quadratic formula should exclude complex numbers

**Common Deductions:**

- Missing Unix commands in code blocks (-5 points each)
- Incorrect directory structure (-10 points)
- Documents that don't render (-15 points)
- Missing screenshot (-5 points)
- Wrong coefficient file location (-5 points)
