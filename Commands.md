# Git Commands Cheat Sheet

### 1. **Initialize a Repository**
`git init`  
*Creates a new Git repository.*

---

### 2. **Clone a Repository**
`git clone <repository-url>`  
*Copies a remote repository to your local machine.*

---

### 3. **Check Repository Status**
`git status`  
*Shows the status of changes in the working directory.*

---

### 4. **Add Files to Staging Area**
`git add <file-name>`  
*Stages a file for the next commit.*

`git add .`  
*Stages all files for the next commit.*

---

### 5. **Commit Changes**
`git commit -m "Commit message"`  
*Commits staged changes with a message describing the changes.*

---

### 6. **Check Commit History**
`git log`  
*Displays the commit history.*

---

### 7. **Create a New Branch**
`git branch <branch-name>`  
*Creates a new branch.*

---

### 8. **Switch to a Branch**
`git checkout <branch-name>`  
*Switches to the specified branch.*

---

### 9. **Create and Switch to a New Branch**
`git checkout -b <branch-name>`  
*Creates and switches to a new branch in one command.*

---

### 10. **Merge a Branch**
`git merge <branch-name>`  
*Merges the specified branch into the current branch.*

---

### 11. **Push Changes to Remote Repository**
`git push origin <branch-name>`  
*Sends your local commits to the remote repository.*

---

### 12. **Pull Changes from Remote Repository**
`git pull origin <branch-name>`  
*Fetches and merges changes from the remote repository to your local branch.*

---

### 13. **View Remote Repositories**
`git remote -v`  
*Lists the remote repositories linked to your local repository.*

---

### 14. **Remove a File from Tracking**
`git rm <file-name>`  
*Removes a file from the working directory and stages its removal.*

---

### 15. **Undo Changes in Staging Area**
`git reset <file-name>`  
*Removes a file from the staging area.*

---

### 16. **Undo the Last Commit (Keep Changes)**
`git reset --soft HEAD^`  
*Undoes the last commit but keeps the changes in the working directory.*

---

### 17. **View Differences Between Commits**
`git diff`  
*Shows the differences between the working directory and the staging area.*

---

### 18. **Create a Tag**
`git tag <tag-name>`  
*Creates a tag at the current commit.*

---

### 19. **Delete a Branch**
`git branch -d <branch-name>`  
*Deletes a branch (only if it’s merged).*

`git branch -D <branch-name>`  
*Force deletes a branch, even if not merged.*

---

### 20. **Stash Changes**
`git stash`  
*Temporarily saves changes and cleans your working directory.*

---

### 21. **Apply Stash**
`git stash apply`  
*Applies the most recent stash to the working directory.*

---

### 22. **Show Git Configuration**
`git config --list`  
*Displays the current Git configuration.*

---

This cheat sheet covers the most commonly used Git commands. Feel free to add or modify it as you go!
