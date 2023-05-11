# all Git commands

As mentioned earlier, Git has many commands, options, and subcommands, and explaining every single command in detail would take a lot of time and space. However, here is a list of all Git commands with a brief explanation of what each command does:

**Configuration:**

- `git config`: Used to set configuration values for Git.
- `git config --global`: Used to set global configuration values for Git.

**Creating and Cloning Repositories:**

- `git init`: Initializes a new Git repository in the current directory.
- `git clone`: Creates a local copy of a remote repository.

**Basic Workflow:**

- `git add`: Adds changes to the staging area.
- `git commit`: Records changes to the repository with a message describing the changes.
- `git status`: Shows the status of the current working directory.
- `git diff`: Shows the differences between the working directory and the staging area.
- `git log`: Shows the commit history.

**Branching and Merging:**

- `git branch`: Lists all local branches in the current repository.
- `git checkout`: Switches to a different branch.
- `git merge`: Merges two or more branches together.
- `git rebase`: Applies changes from one branch to another.
- `git cherry-pick`: Applies the changes of a single commit from one branch to another.

**Collaboration:**

- `git fetch`: Retrieves the latest changes from a remote repository.
- `git pull`: Fetches the latest changes and merges them into the current branch.
- `git push`: Pushes changes to a remote repository.
- `git remote`: Manages remote repositories.
- `git submodule`: Manages submodules within a repository.
- `git clone --recursive`: Clones a repository and its submodules.

**Undoing Changes:**

- `git reset`: Resets changes in the staging area.
- `git revert`: Reverts a commit and creates a new commit that undoes the changes.
- `git clean`: Removes untracked files from the working directory.
- `git stash`: Stashes changes temporarily, allowing you to switch branches without committing changes.

**Viewing and Comparing Changes:**

- `git show`: Shows the changes introduced by a commit.
- `git blame`: Shows who last modified each line of a file and when.
- `git bisect`: Finds the commit that introduced a bug.

**Tags:**

- `git tag`: Creates, lists, and deletes tags.
- `git tag -a`: Creates an annotated tag with a message describing the tag.

**Git Hooks:**

- `pre-commit`: Runs before a commit is made.
- `post-commit`: Runs after a commit is made.
- `pre-rebase`: Runs before a rebase is started.
- `post-merge`: Runs after a merge is completed.

**Other Useful Commands:**

- `git archive`: Creates a tar or zip archive of a repository.
- `git blame`: Shows who last modified each line of a file and when.
- `git bisect`: Finds the commit that introduced a bug.
- `git grep`: Searches the contents of files for a regular expression.
- `git reflog`: Shows a log of changes to the Git references (i.e. branches and tags).
- `git fsck`: Verifies the integrity of the Git repository.
- `git remote add`: Adds a remote repository.
- `git remote rm`: Removes a remote repository.
- `git submodule add`: Adds a submodule to a repository.
- `git submodule init`: Initializes a submodule.
- `git submodule update`: Updates the contents of a submodule.

These are some of the most commonly used Git commands that should be sufficient for most use cases. However
