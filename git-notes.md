# Git Basics

Git is a version control system that helps us track changes in files and manage different versions of a project.

GitHub is a platform used to store Git repositories online, share projects, and collaborate with other developers.


### 1. `git init`

**Description:**
- Creates a new Git repository in the current folder.Starts tracking the project using Git.

**Example:**
```bash
git init
```

### 2.`git clone`

**Description:**
- Downloads a copy of an existing Git repository. Copies the project files and Git history to your computer.

**Example:**
```bash
git clone https://github.com/username/project.git
```


### 3. `git status`

**Description:**
- Shows the current status of files. Tells us which files are modified, staged, or untracked.

**Example:**
```bash
git status
```

### 4.`git diff`

**Description:**
- Shows the changes made to files that are not yet staged.

**Example:**
```bash
git diff
```

### 5.`git log`

**Description:**
- Shows the history of commits made in the repository.

**Example:**
```bash
git log
```


### 6. `git add`

**Description:**
- Adds file changes to the staging area. Prepares the changes for the next commit.

**Example:**
```bash
git add README.md
```

To stage all changes:
```bash
git add .
```

### 7. `git commit`

**Description:**
- Saves the staged changes as a commit in Git history.Uses a message to describe the changes.

**Example:**
```bash
git commit -m "Add Git basics notes"
```


### 8. `git push`

**Description:**
- Uploads local commits to a remote repository, such as GitHub.Shares your committed changes online.

**Example:**
```bash
git push origin main
```

### 9.`git pull`

**Description:**
- Downloads new changes from a remote repository. Integrates those changes into your current branch.

**Example:**
```bash
git pull origin main
```

### 10. `git fetch`

**Description:**
- Downloads new commits and updates remote-tracking information. Does not automatically merge those changes into your current branch.

**Example:**
```bash
git fetch origin
```

