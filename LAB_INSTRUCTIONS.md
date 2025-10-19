# Git and GitHub Lab Instructions

## Overview
This lab will help you complete the Coursera Git and GitHub assignment. Follow these steps carefully to earn all 20 points.

## Part 1: GitHub UI (12 points)

### Task 1: Repository URL (2 pts)
1. Create a new repository on GitHub
2. Upload all the files we've created (LICENSE, README.md, CODE_OF_CONDUCT.md, CONTRIBUTING.md, simple-interest.sh)
3. Save the repository URL for submission

### Task 2: Apache 2.0 License (2 pts)
✅ **COMPLETED** - The LICENSE file is already created with Apache 2.0 license

### Task 3: README.md (2 pts)
✅ **COMPLETED** - The README.md file is already created

### Task 4: CODE_OF_CONDUCT (2 pts)
✅ **COMPLETED** - The CODE_OF_CONDUCT.md file is already created

### Task 5: CONTRIBUTING.md (2 pts)
✅ **COMPLETED** - The CONTRIBUTING.md file is already created

### Task 6: simple-interest.sh (2 pts)
✅ **COMPLETED** - The simple-interest.sh script is already created

## Part 2: Git CLI (8 points)

### Prerequisites
- Git installed on your system
- GitHub account
- Personal Access Token (generate from GitHub Settings > Developer settings > Personal access tokens)

### Task 1: Fork Repository (2 pts)
1. Go to the original repository (you'll need the URL from your instructor)
2. Click "Fork" button
3. Save the forked repository URL

### Task 2: Fix Typo and Merge (2 pts)
1. Clone your forked repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   cd YOUR_REPO_NAME
   ```

2. Create a new branch:
   ```bash
   git checkout -b bug-fix-typo
   ```

3. Edit README.md and change the footer from "2022 XYZ, Inc." to "2023 XYZ, Inc."

4. Add and commit changes:
   ```bash
   git add README.md
   git commit -m "Fix typo: Update copyright year from 2022 to 2023"
   ```

5. Push to your branch:
   ```bash
   git push origin bug-fix-typo
   ```

6. Switch to main branch and merge:
   ```bash
   git checkout main
   git merge bug-fix-typo
   ```

7. **Take a screenshot** showing the merge operation and save as `merge_branches.png`

### Task 3: Revert and Create Pull Request (2 pts)
1. Create a new branch:
   ```bash
   git checkout -b bug-fix-revert
   ```

2. Revert the previous change:
   ```bash
   git revert HEAD~1
   ```

3. Push the revert:
   ```bash
   git push origin bug-fix-revert
   ```

4. Go to GitHub and create a Pull Request from `bug-fix-revert` to the original repository's main branch
5. **Save the PR URL** for submission

### Task 4: Check Branches (2 pts)
1. Go to your repository's branches page: `https://github.com/YOUR_USERNAME/YOUR_REPO_NAME/branches`
2. **Save this URL** for submission

## Files to Submit

### URLs to Save:
1. **Forked Repository URL**: `https://github.com/YOUR_USERNAME/YOUR_REPO_NAME`
2. **Pull Request URL**: `https://github.com/ORIGINAL_OWNER/ORIGINAL_REPO/pull/NUMBER`
3. **Branches Page URL**: `https://github.com/YOUR_USERNAME/YOUR_REPO_NAME/branches`

### Screenshots:
1. **merge_branches.png**: Screenshot showing the merge operation

## Important Notes

- Use your GitHub Personal Access Token as password when prompted
- Make sure to work in the correct branches
- Test your script before committing
- Follow the exact naming conventions for branches
- Save all URLs in a notepad for easy submission

## Troubleshooting

If you encounter issues:
1. Check your Git configuration: `git config --list`
2. Verify your GitHub credentials
3. Ensure you're in the correct directory
4. Check branch names match exactly: `bug-fix-typo` and `bug-fix-revert`

## Scoring Checklist

### Part 1 (12 points):
- [ ] Repository URL submitted (2 pts)
- [ ] Apache 2.0 LICENSE file present (2 pts)
- [ ] README.md file present (2 pts)
- [ ] CODE_OF_CONDUCT.md file present (2 pts)
- [ ] CONTRIBUTING.md file present (2 pts)
- [ ] simple-interest.sh file present (2 pts)

### Part 2 (8 points):
- [ ] Forked repository URL submitted (2 pts)
- [ ] Merge screenshot submitted (2 pts)
- [ ] Pull request URL submitted (2 pts)
- [ ] Branches page URL submitted (2 pts)

**Total: 20 points**
