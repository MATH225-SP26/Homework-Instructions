# Homework Instructions

## Overview

This folder contains all homework assignments for the Introduction to Data Science course. Each assignment builds on skills from previous weeks and introduces new concepts progressively throughout the semester.

## File Organization

Each homework assignment is contained in its own subfolder (e.g., `HW01/`, `HW02/`, etc.). Within each folder, you'll find:

- **`.Rmd` file** - The R Markdown document where you'll complete your work
- **`img/` folder** - Images and graphics used in the assignment
- **Supporting files** - Data files, scripts, or other materials specific to that assignment

## ⚠️ IMPORTANT: Fork First, Then Clone!

**DO NOT clone this repository directly!** If you do, you won't be able to push your work.

### One-Time Setup (Do this at the beginning of the semester)

1. **Fork the repository** to your own GitHub account:
   - Go to the course homework-instructions repository on GitHub
   - Click the **Fork** button in the top-right corner
   - This creates your own copy of the repository under your GitHub account

2. **Clone YOUR forked repository** to JupyterHub:
   - In JupyterHub, go to RStudio
   - Click **File → New Project → Version Control → Git**
   - Paste the URL of **YOUR forked repository** (not the course repository!)
   - Click **Create Project**

3. **Verify you're working in your fork:**
   - In RStudio, look at the Git pane
   - The repository name should be `YourUsername/homework-instructions`
   - NOT `CourseOrganization/homework-instructions`

### Why Fork?

- **Forking** creates your own copy of the repository under your GitHub account
- You have full permission to push changes to your fork
- The course staff can still see your work
- Multiple students can work independently without conflicts

## Workflow for Each Assignment

### Starting Each Assignment

1. Navigate to the appropriate homework folder (e.g., `HW01/`)
2. Open the `.Rmd` file
3. Update the YAML with your name
4. Knit to make sure it compiles
5. Commit with message: `"Updated author name"`
6. Push to **your forked repository** on GitHub

### While Working
```
Work on exercises → Knit → Commit → Push (to YOUR fork)
```

**Important:** 
- You should commit and push your work multiple times throughout each assignment, not just at the end!
- Always push to YOUR forked repository
- Your commits will show up under your GitHub username

### Finishing an Assignment

1. Review all answers for completeness
2. Check that all code chunks are properly labeled
3. Knit the entire document
4. Commit and push all changes to your fork
5. Verify everything is on GitHub (in YOUR fork)
6. Knit to PDF (if required) and submit to Canvas

## Assignment Overview

| HW | Topic | Key Skills |
|:---|:------|:-----------|
| **HW 01** | Pet names | R basics, Git/GitHub workflow, data exploration |
| **HW 02** | Airbnb in Edinburgh | ggplot2, faceting, pipelines, visualization interpretation |
| **HW 03** | Traffic accidents | Density plots, creating new variables, custom visualizations |
| **HW 04** | College majors | Summary statistics, distributions, logical operators, filtering |
| **HW 05** | Legos | Data wrangling, string manipulation, complex pipelines |
| **HW 06** | Money in politics | Web scraping, writing functions, iteration, data cleaning |
| **HW 07** | DC bike rentals | Factor recoding, linear regression, model interpretation |
| **HW 08** | Exploring GSS | Survey data, missing values, categorical recoding, modeling |
| **HW 09** | Modeling GSS | tidymodels workflow, cross-validation, bootstrap confidence intervals |

## Knit/Commit/Push Pattern

You'll see this reminder throughout assignments:

🧶 **Knit** → ✅ **Commit** → ⬆️ **Push**

This means:
1. Click the **Knit** button to generate output
2. Go to the **Git** pane → **Diff** → Check all changed files
3. Write a meaningful **commit message**
4. Click **Commit**
5. Click **Push** (to your forked repository)

## Tips for Success

### General Tips
- Start early! Don't wait until the deadline
- Read the entire assignment before starting
- Ask for help if you're stuck for more than 20 minutes
- Use office hours and discussion forums

### Technical Tips
- Always load packages at the beginning (`library(tidyverse)`, etc.)
- Read error messages carefully - they often tell you what's wrong
- Use `?function_name` to access help documentation
- Use `View(dataset)` in the Console to explore data
- Test code chunks individually before knitting the whole document

### Git/GitHub Tips
- **Make sure you forked the repository first!**
- Commit messages should be brief but descriptive
- Push regularly so your work is backed up
- If push fails, you might be trying to push to the course repo instead of your fork
- Check YOUR forked repository on GitHub after pushing to verify your work is there

## Common Issues and Solutions

### "Permission denied" or "403 error" when pushing
- **Cause:** You cloned the course repository directly instead of your fork
- **Solution:** You need to fork the repository first, then clone your fork. Ask for help if you've already started working!

### "Error: object not found"
- **Cause:** You referenced a variable/dataset that doesn't exist
- **Solution:** Make sure you loaded the required packages and ran all code chunks in order

### "Error: could not find function"
- **Cause:** Package not loaded
- **Solution:** Run `library(tidyverse)` (or whatever package is needed) in your Console

### Knitting fails
- **Cause:** Error in one of your code chunks
- **Solution:** Run each code chunk individually to find which one has the error

### Git pane shows many files but won't commit
- **Cause:** You haven't checked the boxes next to files
- **Solution:** Click the checkbox next to each file you want to commit

### Can't push to GitHub
- **Cause:** Either authentication issue or trying to push to course repo instead of your fork
- **Solution:** 
  1. Check that you're working in YOUR fork (look at the Git pane)
  2. Try pulling first, then pushing again
  3. If still failing, ask for help with authentication

### Not sure if I'm in my fork or the course repository
- **Check in RStudio:** Look at the Git pane - it should show `YourUsername/homework-instructions`
- **Check on GitHub:** Your commits should appear in your fork at `github.com/YourUsername/homework-instructions`

## Getting Help

1. **Check the Common Errors section** at the end of each assignment
2. **Review lecture materials and labs** - homework builds on these
3. **Ask classmates** on the discussion board (but don't share code!)
4. **Attend office hours** - instructors are here to help!
5. **Email your instructor** if you're completely stuck

## Assignment Submission

Most assignments require two submissions:

1. **GitHub** - Your final committed and pushed work in YOUR FORK (we grade what we see in your forked repo)
2. **Canvas** - A PDF of your knitted document

**To generate a PDF:**
1. Click the **Knit** dropdown (next to the Knit button)
2. Select **Knit to tufte_handout**
3. Download the PDF from your Files pane
4. Upload to Canvas

## Important Reminders

- ✅ **Fork FIRST, then clone** - don't skip the forking step!
- ✅ **Commit and push regularly** - don't lose your work!
- ✅ **Push to YOUR fork** - check the repository name in Git pane
- ✅ **Knit often** - catch errors early
- ✅ **Read instructions carefully** - follow all requirements
- ✅ **Label code chunks** - use informative, unique labels
- ✅ **Write complete sentences** - interpretations should be clear and in context
- ✅ **Check YOUR fork on GitHub** - verify your work is there before the deadline
- ✅ **Start early** - give yourself time to get help if needed

## Academic Integrity

- You may discuss concepts with classmates
- You may not share code or written answers
- All work you submit must be your own
- Cite any external resources you use (beyond course materials)

## Quick Reference: Fork vs. Clone

| Action | What it does | When to do it |
|:-------|:-------------|:--------------|
| **Fork** | Creates your own copy of a repository under your GitHub account | Once at the beginning of the semester |
| **Clone** | Downloads a repository to your local machine (JupyterHub) | Once after forking |
| **Commit** | Saves a snapshot of your changes locally | After completing each exercise |
| **Push** | Uploads your commits to GitHub (your fork) | After each commit or group of commits |

---

**Questions about forking or cloning?** Don't hesitate to ask during class, office hours, or on the discussion board. Getting this setup right at the beginning will save you headaches later! 🎓
