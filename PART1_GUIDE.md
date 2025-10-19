# Part 1: GitHub UI - Complete Guide

## Overview
This guide will help you complete Part 1 of the Git and GitHub assignment (12 points total).

## Files Ready for Upload

All required files are now prepared and ready for your GitHub repository:

### ✅ Task 1: Repository URL (2 pts)
**Action Required**: Create a new GitHub repository
1. Go to GitHub.com and click "New repository"
2. Name it: `github-final-project`
3. Make it **public**
4. ✅ Check "Add a README file"
5. ✅ Check "Choose a license" and select **Apache 2.0**
6. Click "Create repository"
7. **SAVE THE REPOSITORY URL** in your notepad

### ✅ Task 2: Apache 2.0 License (2 pts)
**Status**: COMPLETED
- The LICENSE file is already created with Apache 2.0 license
- When you create the repository with Apache 2.0 license, GitHub will automatically add this

### ✅ Task 3: README.md (2 pts)
**Status**: COMPLETED
- README.md file is ready with the exact content specified:
  - Calculator description
  - Input format (p, t, r)
  - Output format (simple interest = p*t*r)

### ✅ Task 4: CODE_OF_CONDUCT.md (2 pts)
**Status**: COMPLETED
- CODE_OF_CONDUCT.md file is ready with Contributor Covenant template

### ✅ Task 5: CONTRIBUTING.md (2 pts)
**Status**: COMPLETED
- CONTRIBUTING.md file is ready with the specified content

### ✅ Task 6: simple-interest.sh (2 pts)
**Status**: COMPLETED
- simple-interest.sh file is ready with the exact script provided in the assignment

## Step-by-Step Instructions

### Step 1: Create GitHub Repository
1. Go to https://github.com
2. Click the "+" icon → "New repository"
3. Repository name: `github-final-project`
4. Description: (optional)
5. Make it **Public**
6. ✅ Check "Add a README file"
7. ✅ Check "Choose a license" → Select "Apache License 2.0"
8. Click "Create repository"

### Step 2: Upload Files
You need to upload these files to your repository:

1. **README.md** - Replace the auto-generated one with our prepared version
2. **CODE_OF_CONDUCT.md** - Upload the prepared file
3. **CONTRIBUTING.md** - Upload the prepared file  
4. **simple-interest.sh** - Upload the prepared script

### Step 3: Verify All Files
Your repository should contain:
- ✅ README.md (with calculator description)
- ✅ LICENSE (Apache 2.0 - auto-generated)
- ✅ CODE_OF_CONDUCT.md (Contributor Covenant)
- ✅ CONTRIBUTING.md (contribution guidelines)
- ✅ simple-interest.sh (bash script)

### Step 4: Save Repository URL
**IMPORTANT**: Save your repository URL in a notepad:
```
https://github.com/YOUR_USERNAME/github-final-project
```

## Files to Upload

### README.md
```
# Simple Interest Calculator

A calculator that calculates simple interest given principal, annual rate of interest and time period in years.

## Input:
   p, principal amount
   t, time period in years
   r, annual rate of interest

## Output
   simple interest = p*t*r
```

### simple-interest.sh
```bash
#!/bin/bash
# This script calculates simple interest given principal,
# annual rate of interest and time period in years.
# Do not use this in production. Sample purpose only.
# Author: Upkar Lidder (IBM)
# Additional Authors:
# <your GitHub username>
# Input:
# p, principal amount
# t, time period in years
# r, annual rate of interest
# Output:
# simple interest = p*t*r
echo "Enter the principal:"
read p
echo "Enter rate of interest per year:"
read r
echo "Enter time period in years:"
read t
s=`expr $p \* $t \* $r / 100`
echo "The simple interest is: "
echo $s
```

### CONTRIBUTING.md
```
All contributions, bug reports, bug fixes, documentation improvements, enhancements, and ideas are welcome.
```

### CODE_OF_CONDUCT.md
(Use the Contributor Covenant template - already prepared)

## Scoring Checklist

- [ ] **Task 1 (2 pts)**: Repository URL submitted
- [ ] **Task 2 (2 pts)**: Apache 2.0 LICENSE file present
- [ ] **Task 3 (2 pts)**: README.md file with specified content
- [ ] **Task 4 (2 pts)**: CODE_OF_CONDUCT.md file present
- [ ] **Task 5 (2 pts)**: CONTRIBUTING.md file present
- [ ] **Task 6 (2 pts)**: simple-interest.sh file present

**Total: 12 points for Part 1**

## Important Notes

1. **Repository must be PUBLIC**
2. **Repository name must be exactly**: `github-final-project`
3. **All files must be in the root directory**
4. **Save the repository URL for submission**
5. **Verify all 5 files are present before submitting**

## Next Steps

After completing Part 1:
1. Save your repository URL
2. Take screenshots if needed
3. Move to Part 2 (Git CLI) - 8 points
4. Follow the instructions in `LAB_INSTRUCTIONS.md` for Part 2

You're ready to complete Part 1! All files are prepared and match the exact requirements.
