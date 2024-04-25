# What is Git?
* Git is a distributed version control system used for tracking changes in source code during software development. It allows multiple developers to collaborate on projects, maintain a history of changes, and merge modifications seamlessly.

# What is the difference between Git and other version control systems like SVN?
* Git is a distributed version control system, whereas SVN (Subversion) is centralized. In Git, every developer has a complete copy of the repository, allowing them to work offline and commit changes locally before pushing them to a remote repository. SVN requires a constant connection to a central server for most operations.

# Explain the basic Git workflow.
The basic Git workflow involves the following steps:
* Modify files in your working directory.
* Stage the changes you want to commit using git add.
* Commit the staged changes to your local repository using git commit.
* Push your commits to a remote repository using git push.

# What is a repository in Git?
* A Git repository (or repo) is a collection of files and directories along with the entire history of changes made to those files. It contains metadata about the project and all the commits made by contributors.

# What is a commit in Git?
* A commit in Git is a snapshot of the repository at a particular point in time. It represents a set of changes made to the files in the repository and includes a commit message describing the changes.

# What is a branch in Git?
* A branch in Git is a lightweight movable pointer to a commit. It allows developers to work on isolated features or bug fixes without affecting the main codebase. Branches facilitate parallel development and experimentation.

# How do you resolve a merge conflict in Git?
* To resolve a merge conflict in Git, you need to manually edit the conflicted files to resolve the differences. After resolving conflicts, you stage the changes using git add and then commit the merge using git commit.

# What is Git rebase?
* Git rebase is a command used to reapply commits on top of another branch. It allows you to rewrite the commit history by moving, combining, or deleting commits. Rebase is often used to maintain a clean and linear commit history.

# How do you undo the last commit in Git?
* To undo the last commit in Git, you can use the git reset command with the --soft, --mixed, or --hard option depending on whether you want to keep the changes in the staging area or working directory. For example, git reset --soft HEAD~1 will undo the last commit and keep the changes staged.

# What are some best practices for using Git?
* Some best practices for using Git include committing frequently with descriptive commit messages, branching for features or bug fixes, regularly pulling changes from remote repositories, and using Git hooks for automating tasks.
