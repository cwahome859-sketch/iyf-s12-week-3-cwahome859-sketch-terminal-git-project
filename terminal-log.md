# Terminal Commands Log

## 1. Navigation Commands

| Command | What it does |
|---|---|
| `pwd` | Displays the current working directory. |
| `ls` | Lists files and folders. |
| `ls -la` | Displays all files, including hidden files. |
| `cd folder` | Moves into a directory. |
| `cd ..` | Moves one directory backwards. |
| `clear` | Clears the terminal screen. |

## 2. File and Folder Management

| Command | What it does |
|---|---|
| `mkdir folder` | Creates a directory. |
| `mkdir -p a/b` | Creates nested directories. |
| `touch file.txt` | Creates an empty file. |
| `cp file1 file2` | Copies a file. |
| `mv file1 file2` | Moves or renames a file. |
| `rm file.txt` | Deletes a file. |
| `cat file.txt` | Displays file contents. |

## 3. Searching Commands

| Command | What it does |
|---|---|
| `find . -type f`= Finds all files. 
| `find . -name "*.html"`= Finds HTML files. 
| `grep "JavaScript" file.txt`= Searches for JavaScript. 
| `grep -i "word" file.txt`= Searches without case sensitivity. 
| `grep -n "word" file.txt`= Displays matching line numbers. 
| `grep -r "word" .` = Searches recursively.

## 4. Bash Commands

| Command | What it does |
|---|---|
| `echo "Hello"` | Prints text. |
| `read name` | Accepts user input. |
| `chmod +x script.sh` | Makes a script executable. |
| `./script.sh` | Executes a shell script. |

## 5. Git Commands

| Command | What it does |
|---|---|
| `git init` | Initializes a Git repository. |
| `git status` | Displays repository status. |
| `git add .` | Stages changes. |
| `git commit -m "message"` | Creates a commit. |
| `git log --oneline` | Displays commit history. |
| `git branch` | Lists branches. |
| `git switch -c branch-name` | Creates and switches branches. |
| `git switch main` | Switches to main. |
| `git merge branch-name` | Merges a branch. |
| `git branch -d branch-name` | Deletes a merged branch. |
| `git remote -v` | Displays remote repositories. |
| `git push` | Uploads commits to GitHub. |
| `git pull` | Downloads and integrates remote changes. |

## 6. Git Conflict Resolution

| Command | What it does |
|---|---|
| `git merge branch-name` | Attempts to merge another branch. |
| `git status` | Identifies conflicting files. |
| `git add file.txt` | Marks the conflict as resolved after editing. |
| `git commit` | Completes the merge commit. |Documentation updated.
