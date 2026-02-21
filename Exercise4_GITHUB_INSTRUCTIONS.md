# Exercise 4: GitHub Collaboration - Step-by-Step Guide

## Prerequisites
- GitHub account created
- Git installed and configured with your GitHub credentials

## Steps to Complete

### Step 1: Fork a Sample Repository on GitHub
1. Go to a sample repository (e.g., https://github.com/octocat/Hello-World)
2. Click the "Fork" button in the top-right corner
3. This creates a copy of the repository under your GitHub account

### Step 2: Clone the Repository Locally
```bash
git clone https://github.com/YOUR_USERNAME/Hello-World.git
cd Hello-World
git config user.email "your-email@example.com"
git config user.name "Your Name"
```

### Step 3: Create a New Branch
```bash
git checkout -b add-my-contribution
```

### Step 4: Make Changes and Commit
```bash
# Edit files or add new content
echo "My contribution" >> README.md
git add README.md
git commit -m "Add my contribution to the project"
```

### Step 5: Push to Your Fork
```bash
git push origin add-my-contribution
```

### Step 6: Create a Pull Request
1. Visit your forked repository on GitHub
2. You'll see a "Compare & pull request" button
3. Click it and fill in the pull request description
4. Click "Create pull request"
5. The maintainers will review your changes

## Verification Commands
After pushing, verify your push:
```bash
git log --oneline
git branch -v
```

## Notes
- A pull request is a way to propose changes to a repository
- The maintainers of the original repository will review your changes
- They may request modifications before merging your PR
- Once approved, your code becomes part of the project!
