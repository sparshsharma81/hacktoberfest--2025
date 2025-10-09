## 🎯 How to Participate

### Find Issues to Work On
Browse our issues and look for:
- `good first issue` - Perfect for beginners
- `hacktoberfest` - Hacktoberfest-ready tasks
- `help wanted` - Areas where we need assistance

## 🚀 Getting Started - Step by Step

### Prerequisites

Before you begin, ensure you have:
- [Git](https://git-scm.com/downloads) installed on your computer
- A [GitHub account](https://github.com/signup)
- A code editor of your choice

### Step 1: Fork the Repository

1. Click the **Fork** button at the top right of this repository
2. This creates a copy of the repository in your GitHub account

### Step 2: Clone Your Fork

Open your terminal or command prompt and run:

```bash
# Clone the repository to your local machine
git clone https://github.com/IEEE-Student-Branch-NSBM/hacktoberfest-2025.git

# Navigate into the project directory
cd hacktoberfest-2025
```
### Step 3: Set Up Upstream Remote

This connects your local repository to the original repository:

```bash
# Add the original repository as "upstream"
git remote add upstream https://github.com/IEEE-Student-Branch-NSBM/hacktoberfest-2025.git

# Verify your remotes
git remote -v
```

You should see:
- `origin` - your fork
- `upstream` - the original repository

### Step 4: Install Dependencies

```bash
# Follow the project-specific installation instructions
# Check for setup files or installation guides in the repository
```

## 🤝 Contributing to the Project

### Step 1: Sync Your Fork

Before starting work, make sure your fork is up to date:

```bash
# Switch to the main branch
git checkout main

# Fetch updates from upstream
git fetch upstream

# Merge updates into your local main branch
git pull upstream main

# Push updates to your fork
git push origin main
```

### Step 2: Create a New Branch

Always create a new branch for your work:

```bash
# Create and switch to a new branch
git checkout -b your-branch-name
```

**Branch Naming Conventions:**
- `feature/add-new-functionality`
- `fix/resolve-bug-description`
- `docs/update-documentation`
- `refactor/improve-code-structure`

### Step 3: Make Your Changes

1. Open the files you need to modify in your code editor
2. Make your changes carefully
3. Save your work
4. Test your changes thoroughly

### Step 4: Stage Your Changes

```bash
# Check which files were modified
git status

# Stage specific files
git add filename1 filename2

# Or stage all changes
git add .
```

### Step 5: Commit Your Changes

Write a clear, descriptive commit message:

```bash
git commit -m "Type: Brief description of changes"
```

**Commit Message Types:**
- `Feat:` when adding new features or files
- `Fix:` when fixing bugs
- `Update:` when updating existing functionality
- `Remove:` when removing code or files
- `Refactor:` when restructuring code
- `Docs:` when updating documentation
- `Style:` when formatting code

**Examples:**
```bash
git commit -m "Feat: User authentication feature"
git commit -m "Fix: Resolve login button issue"
git commit -m "Docs: Update installation instructions"
```

### Step 6: Push Your Changes

Push your branch to your fork on GitHub:

```bash
git push origin your-branch-name
```

### Step 7: Create a Pull Request

1. Go to your fork on GitHub
2. You'll see a banner saying "Compare & pull request" - click it
3. Fill out the pull request form:
   - **Title:** Clear, concise description of your changes
   - **Description:** Explain what you did and why
   - **Reference issues:** Use "Fixes #123" or "Closes #123"
   - **Add screenshots:** If your changes affect the UI
4. Click **Create pull request**

### Step 8: Respond to Feedback

- Maintainers may request changes to your PR
- Make the requested changes in your local branch
- Commit and push the updates
- The PR will automatically update

```bash
# Make requested changes
git add .
git commit -m "Update: Address review feedback"
git push origin your-branch-name
```
