

# GitHub Commands for Beginners

Here are some basic GitHub commands and their usage:

## Configuration

**1. Setting your Git username:**

```bash
git config --global user.name "Your Name"
```

**2. Setting your Git email:**

```bash
git config --global user.email "youremail@example.com"
```

## Create & Clone Repositories

**3. Initialize a local directory as a Git repository:**

```bash
git init
```

**4. Clone an existing repository:**

```bash
git clone https://github.com/username/repo.git
```

## Local Changes

**5. Check the status of your files:**

```bash
git status
```

**6. Add all new and changed files to the staging area:**

```bash
git add .
```

**7. Commit the changes:**

```bash
git commit -m "Commit message"
```

## Branching & Merging

**8. List all branches:**

```bash
git branch
```

**9. Create a new branch:**

```bash
git branch new-branch
```

**10. Switch to a branch:**

```bash
git checkout branch-name
```

**11. Merge a branch into the active one:**

```bash
git merge branch-name
```

**12. Delete a branch:**

```bash
git branch -d branch-name
```

## Update & Publish

**13. Pull updates from the remote repository to local repository:**

```bash
git pull
```

**14. Push local changes to the remote repository:**

```bash
git push origin branch-name
```

## Undo commits

**15. Undo the last commit:**

```bash
git revert HEAD
```

**16. Reset your repo to the last commit:**

```bash
git reset --hard HEAD
```

## Others

**17. Show the commit history:**

```bash
git log
```

Remember, the usage of GitHub involves a variety of practices. It's important to learn not only the commands, but also when to use them appropriately. For instance, always make sure to pull the latest changes from the main branch before starting to work on a feature. Likewise, try to keep your commits atomic, meaning each commit should represent a single logical change.

