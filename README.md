# Git Quick Reference Guide

> This is a quick reference guide for beginners to Git version control. It provides step-by-step instructions on common Git commands and workflows, from initializing a repository to collaborating with others and managing project history. Whether you're new to Git or need a refresher, this guide aims to help you navigate through the essential concepts and commands efficiently

## Getting Started

1. **Create a New Repository:** Initialize a new Git repository for your project.
    ```
    git init
    ```

2. **Add Files to the Repository:** Add your project files to the repository.
    ```
    git add <file(s)>
    ```

3. **Commit Changes with a Message:** Record the changes to the repository.
    ```
    git commit -m "Initial commit"
    ```

4. **Connect to a Remote Repository:** Link your local repository to a remote repository on GitHub (replace `<repository-url>` with your GitHub repository URL).
    ```
    git remote add origin <repository-url>
    ```

5. **Push Changes to GitHub:** Upload your local commits to the remote repository on GitHub.
    ```
    git push -u origin master
    ```

## Making Changes

6. **Add Changes to the Staging Area:** Prepare changes for commit.
    ```
    git add <file(s)>
    ```

7. **Commit Changes with a Message:** Record changes to the repository.
    ```
    git commit -m "Commit message"
    ```

## Collaboration

8. **Push Changes to a Remote Repository:** Upload local commits to a remote repository.
    ```
    git push
    ```

9. **Pull Changes from a Remote Repository:** Fetch and merge changes from a remote repository.
    ```
    git pull
    ```

10. **Create a New Branch:** Start working on a new feature or bug fix.
    ```
    git branch <branch-name>
    ```

11. **Switch to a Branch:** Navigate between different branches.
    ```
    git checkout <branch-name>
    ```

12. **Merge Changes from Another Branch:** Combine changes from one branch into another.
    ```
    git merge <branch-name>
    ```

## Miscellaneous

13. **Check Repository Status:** View the status of tracked and untracked files.
    ```
    git status
    ```

14. **View Commit History:** See a log of commits.
    ```
    git log
    ```

15. **List Remote Repositories:** Display configured remote repositories.
    ```
    git remote -v
    ```

16. **Fetch Objects and References from Another Repository:** Download objects and refs from another repository.
    ```
    git fetch
    ```

17. **List, Create, or Delete Tags:** Manage tags for marking important points in history.
    ```
    git tag
    ```


With these basic Git commands, you can efficiently manage your version-controlled projects and collaborate with others. Feel free to explore more advanced Git features as you become more comfortable with the basics.


> Dizzpy | Happy coding! 🖥️🥰
