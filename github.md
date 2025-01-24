# **Git Commands Cheatsheet**

## **1. Initialize a Git Repository**

Create a new Git repository in your project directory:

```bash
git init
```

_Initializes an existing directory as a Git repository._

---

## **2. Stage Changes**

Add all changes (new, modified, and deleted files) to the staging area:

```bash
git add .
```

_Stages all changes in the current directory._

---

## **3. Commit Changes**

Save your staged changes with a descriptive message:

```bash
git commit -m 'Added my project'
```

_Commits the staged changes with the provided message._

---

## **4. Add a Remote Repository**

Link your local repository to a remote GitHub repository:

```bash
git remote add origin https://github.com/EthanRodrigues001/appwrite-auth
```

_Associates your repository with the remote GitHub repository._

---

## **5. Push Changes to Remote**

Upload your local commits to the remote repository:

```bash
git push -u origin main
```

_Pushes changes to the `main` branch on GitHub._

---

## **6. Pull Changes from Remote**

Fetch and merge the latest changes from the remote repository:

```bash
git pull origin main
```

_Downloads and integrates updates from the remote `main` branch._

---

## **7. Check Repository Status**

View the current state of your working directory and staging area:

```bash
git status
```

_Displays the status of tracked and untracked files._

---

## **8. Reset Changes**

Unstage all changes and revert to the last committed state:

```bash
git reset .
```

_Removes changes from the staging area but keeps them in the working directory._

---
