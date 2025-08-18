# Basic Git Commands and How to Use Them

Git is a distributed version control system widely used for tracking changes in source code during software development. Here are some of the most fundamental Git commands, their purposes, and example usages.

---

## 1. `git status`

**Purpose:** Shows the current state of the working directory and staging area. It displays which changes have been staged, which haven't, and which files aren’t being tracked by Git.

**Example:**
```sh
git status
```
*Output:*  
Displays a list of changed files, files to be committed, and files not staged for commit.

---

## 2. `git init`

**Purpose:** Initializes a new Git repository in the current directory.

**Example:**
```sh
git init
```
*Output:*  
Creates a new `.git` folder in your project, making it a Git repository.

---

## 3. `git clone`

**Purpose:** Creates a copy of a remote repository locally.

**Example:**
```sh
git clone https://github.com/user/repo.git
```
*Output:*  
Copies all files and history from the remote repository to a local folder named `repo`.

---

## 4. `git add`

**Purpose:** Adds changes in the working directory to the staging area, preparing them to be committed.

**Example (add a specific file):**
```sh
git add filename.txt
```
**Example (add all changes):**
```sh
git add .
```
*Output:*  
Files are staged and ready to be committed.

---

## 5. `git commit`

**Purpose:** Records the staged changes to the repository history with a descriptive message.

**Example:**
```sh
git commit -m "Add new feature"
```
*Output:*  
A new commit is created with the provided message.

---

## 6. `git push`

**Purpose:** Uploads your local commits to the remote repository.

**Example:**
```sh
git push origin main
```
*Output:*  
Your commits are sent to the `main` branch on the remote repository named `origin`.

---

## 7. `git pull`

**Purpose:** Fetches and integrates changes from the remote repository into your local branch.

**Example:**
```sh
git pull origin main
```
*Output:*  
Downloads new commits from the remote `main` branch and merges them into your current branch.

---

## Summary Table

| Command         | Purpose                                      | Example                        |
|-----------------|----------------------------------------------|--------------------------------|
| `git status`    | Show current repo state                      | `git status`                   |
| `git init`      | Initialize a new repo                        | `git init`                     |
| `git clone`     | Copy a remote repo locally                   | `git clone URL`                |
| `git add`       | Stage changes                                | `git add filename.txt`         |
| `git commit`    | Save staged changes with a message           | `git commit -m "message"`      |
| `git push`      | Send commits to remote repository            | `git push origin main`         |
| `git pull`      | Fetch and merge changes from remote          | `git pull origin main`         |

---

These commands form the foundation of everyday Git usage for most developers.
