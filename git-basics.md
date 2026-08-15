# Git Basics Notes

## What is Git?

Git is a distributed version control system used to track changes in files and collaborate on software projects.

## Common Git Commands

### Initialize a Repository

```bash
git init
```

Creates a new Git repository in the current folder.

### Check Repository Status

```bash
git status
```

Shows modified, staged, and untracked files.

### Add Changes

```bash
git add .
```

Stages changes for the next commit.

### Create a Commit

```bash
git commit -m "message"
```

Saves staged changes with a descriptive message.

### Create a Branch

```bash
git switch -c feature/name
```

Creates and switches to a new feature branch.

### Switch Branches

```bash
git switch main
```

Switches to the main branch.

### Push Changes

```bash
git push
```

Uploads local commits to the remote repository.

### Pull Changes

```bash
git pull
```

Downloads and integrates changes from the remote repository.

### View Commit History

```bash
git log --oneline
```

Displays a concise commit history.

## Git Workflow

A basic Git workflow is:

1. Create or update an Issue.
2. Create a feature branch.
3. Make changes.
4. Stage and commit the changes.
5. Push the branch to GitHub.
6. Open a Pull Request.
7. Review the Pull Request.
8. Merge the Pull Request into `main`.


## Best Practices

* Write clear and meaningful commit messages.
* Use feature branches instead of making feature changes directly on `main`.
* Pull the latest changes before starting new work.
* Review changes through Pull Requests before merging.
* Keep the `main` branch stable.
