# Git Practice

A simple repository to practice basic Git commands like clone, add, commit, and push.

## Usage

1. **Clone the repository:**
    ```
    git clone <repository-url>
    ```
2. **Check the status of your files:**
    ```
    git status
    ```
3. **Add files to staging:**
    ```
    git add <filename>
    ```
    or to add all files:
    ```
    git add .
    ```
4. **View staged changes:**
    ```
    git diff --staged
    ```
5. **Commit your changes:**
    ```
    git commit -m "your commit message"
    ```
6. **View commit history:**
    ```
    git log
    ```
7. **Push changes to remote:**
    ```
    git push
    ```
8. **Pull latest changes from remote:**
    ```
    git pull
    ```
    9. **List all branches:**
        ```
        git branch
        ```
    10. **Create a new branch:**
        ```
        git branch <branch-name>
        ```
    11. **Switch to a branch:**
        ```
            git checkout <branch-name>
            ```
        12. **Undo the last commit (keep changes staged):**
            ```
            git reset --soft HEAD~1
            ```
        13. **Undo the last commit (unstage changes, keep changes in working directory):**
            ```
            git reset --mixed HEAD~1
            ```
        14. **Undo the last commit (discard changes permanently):**
            ```
            git reset --hard HEAD~1
            ```
        15. **Revert a specific commit (create a new commit that undoes changes):**
            ```
            git revert <commit-hash>
            ```