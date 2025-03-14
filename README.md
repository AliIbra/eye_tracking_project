# eye_tracking_project

# Git Workflow Guide

This guide explains how to clone a repository, add a Jupyter Notebook to it, and push the changes to the remote repository.

## Steps to Follow

### 1. Clone the Repository
Navigate to the directory where you want to clone the repository and run:

```bash
git clone <repo-link>
```

Replace `<repo-link>` with the actual repository URL.

### 2. Move the Notebook File
Move the Jupyter Notebook file to the folder where you cloned the repository.

### 3. Check for Changes
Run the following command to check the status of your repository:

```bash
git status
```

This will display any untracked or modified files.

### 4. Stage the Changes
Add all the changes to Git:

```bash
git add .
```

### 5. Verify the Changes
Run `git status` again to confirm that the changes have been staged:

```bash
git status
```

### 6. Commit the Changes
Commit the changes with a descriptive message:

```bash
git commit -m "Added Jupyter Notebook file"
```

### 7. Push to Remote Repository
Push the committed changes to the remote repository:

```bash
git push -u origin main
```

Replace `main` with the appropriate branch name if necessary.

---

Now your changes are successfully uploaded to the repository!

