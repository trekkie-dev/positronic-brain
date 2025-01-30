# Creating a new repository

### What it does:
GIT INIT is used to create a new Git repository(repo).

When you run `git init` in a directory, it creates a subdirectory called `.git` which contains the necessary configuration files for a repository.

It turns the directory into a Gir repository, making it ready to track changes and manage file versions.

### Basic usage:
To initialize a new repository, navigate to your project directory and run this command via the terminal:
```
git init
```

Alternatively, you can create to the project folder using the `mkdir` command in the terminal:
```
mkdir my-project    // creates the directory `my-project`
cd my-project       // `cd` navigates to the created directory
git init
```