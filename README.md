# Git
Git Tutorial in simple words

# Git Basics

- `ls`: Lists the files in the current directory.
- `cd <directory>`: Change the working directory to `<directory>`.
- `code .`: Opens the current directory in Visual Studio Code (VS Code).

# Git Version Control

- `git add <filename>`: Stages the specified file for the next commit.
- `git status`: Shows the status of your working directory and staged changes.
- `git commit -m "message"`: Records changes in the repository with a descriptive message.
- `git push`: Pushes your local commits to the remote repository on platforms like GitHub.
- `git pull`: Fetches and merges changes from the remote repository into your local branch.
- `git commit -am "message"`: Stages and commits all modified files with the specified commit message.

# Handling Conflicts

- **Git Conflicts**: Occur when multiple people modify the same part of a file independently. Resolving conflicts involves manually choosing which changes to keep.

# Git Commit Hash

- Each Git commit has a unique commit hash for identification.

# Resetting Changes

- `git reset`: Unstages changes, leaving your working directory unchanged.
- `git reset --hard <commit hash>`: Resets your branch to a specific commit, discarding changes after that commit.
- `git reset --hard origin/master`: Resets your branch to match the `origin/master` branch from the remote repository.

# Branching and Merging

- `git branch`: Lists all local branches, with an asterisk (*) indicating the currently checked-out branch.
- `git checkout -b <new branch>`: Creates and checks out a new branch with the specified name.
- `git switch <branch name>` (Newer Git versions): Switches to the specified branch.
- `git merge <branch name>`: Merges changes from `<branch name>` into the current branch, often used to integrate feature branches into the `master` branch.

Remember to replace `<directory>`, `<filename>`, and `<branch name>` with the actual directory, file, or branch name you intend to use. These notes provide a solid foundation for understanding and working with Git, but Git is a versatile and powerful tool with many advanced features. Continue exploring and practicing to become proficient in version control with Git.
