# all Git commands

As mentioned earlier, Git has many commands, options, and subcommands, and explaining every single command in detail would take a lot of time and space. However, here is a list of all Git commands with a brief explanation of what each command does:

## Basic GIT Commands

The basic GIT commands are as follows:

- `git config` : It is used to set the name of the author and the email address which you want your commitment to addressing.

- `git config –global user.email "[email address]"`
  git config
- `git init` : It is used to start a new git repository. This is generally used at the beginning.
- `git init [repo name]` git init
- `git clone` : This command is used to clone or copy a repository from a URL. This URL generally is a bitbucket server, a stash or any other version control and source code management repository holding service.

- `git clone [URL]` git clone.
- `git add` : It is used to add a file to the staging area. Instead of choosing a single file name, you can also choose to give all filenames with an \*`.`

- `git add (filename)` : add single file.
- `git add .` : add all file.

- ''git commit –m'' It is used to snapshot or record a file in its version history permanently.

git commit –m [type in a message]
Giving a message text at the end of the commit command helps in identifying the details about the commit code.

git commit
git commit –a: This commit command is used to commit any such file which has been added as a result of the git add command. It is also responsible for committing any other files to which you have brought a change to since then.
git commit -a
git commit -a
git diff: As the name suggests, this command is used to display all the differences between the files until the changes have not yet been staged.
git diff
git diff
git diff –staged: It is used to display all the differences between staging area files and the latest version, which might be present.
git diff -staged
git diff -staged
git diff [first branch] [second branch]: This is a very effective command as it is used to display the differences present between the two branches. Generally, a single developer will be working on his individual branch, which will then be combined into a master branch.
git diff [first branch] [second branch]
git diff [first branch] [second branch]
git reset [file]: This command, as the name suggests, is used to unstage a file. Even though it unstages the file, still the contents of the file have stayed intact.
git reset [file]
git reset [file]
Intermediate GIT Commands
The intermediate GIT commands are as follows:

Git reset [commit]: It is used to undo all the changes that have been incorporated as a part of a commit after a specified commit has taken place. This helps in saving the changes locally on the computer.
git rest [commit]
rest [commit]
Git reset –hard [commit]: This command is used to discard all the history and takes us to the last specified commit.
git reset –hard [commit]
reset –hard [commit]
Git status: This is one of the most frequently used as this is used to list down all the files which are ready to be committed.
git status
status
Git rm: As in the Unix, rm is used to remove; in the same way, rm is used to delete the file from the present working directory and is also used to stage the deletion process.
git rm [file]
rm [file]
Git log: This is used for listing down the version history for the current working branch.
git log
log
git log –follow: This is similar to that of git log with the additional difference that it lists the version history for a particular file, which often includes the renaming of the file also.
git log –follow [file]
log –follow [file]
git show: This is used to display the metadata and all the content related changes of a particular commit.
git show [commit]
show [commit]
git tag: This is used to give particular tags to the code commits.
git tag [commitID]
tag [commitID]
git branch: Git branch command is used to list down all the branches that are locally present in the repository.
git branch
git branch
Git branch [branch-name]: This is used to create a new branch.
Git branch [branch-name]
branch [branch-name]
Advanced Commands
The advanced commands are as follows:

Git branch –d [branch name]: It is used to delete the current branch name specified.
git branch –d [branch name]
branch –d [branch name]
Git checkout: It is helpful in switching from one branch to another.
git checkout [branch-name]
checkout [branch-name]

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
