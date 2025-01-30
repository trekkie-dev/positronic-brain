# Cloning a Git repository

The `git clone` command creates a copy of an exisiting repository.

### What it does:
`git clone` creates a local copy or a remote repo, including file history, branches and files.

It also sets up the local repo to track the remote repository. This makes it easier to fetch updates and push changes.

### Basic usages:
Syntax: `git clone <repository-url>`

### Example:
```
git clone https://github.com/user/repository.git
```
This command clones the repo from the url into a directory named `repository`

You can also clone a repository to a specific url by adding the name of the directory to the end of the command:
```
git clone https://github.com/user/repository.git my-directory
```