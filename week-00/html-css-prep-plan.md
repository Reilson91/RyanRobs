# Week 0 HTML/CSS Student Preparation Plan

_Note: Be sure to do all required preparation before class._

## Required
### Presentation by Christian Burk
- [Introduction to Pair Programming video recording](https://web.microsoftstream.com/video/3e43ff28-0a5a-4804-b998-b5239254106a)
- [Introduction to Pair Programming PowerPoint slides](intro-to-pair-programming.pptx)

### Pluralsight

- [Git: The Big Picture by Paolo Perrotta](https://app.pluralsight.com/library/courses/git-big-picture/table-of-contents)

## Optional
- [Getting Started with Git by Aaron Stewart](https://app.pluralsight.com/library/courses/getting-started-git/table-of-contents)

## Resources
- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
- [Git Cheat Sheet](https://www.git-tower.com/blog/git-cheat-sheet)

### More Pluralsight (super-optional)
- [Mastering Git by Paolo Perrotta](https://app.pluralsight.com/library/courses/master-git/table-of-contents)
- [How Git Works by Paolo Perrotta](https://app.pluralsight.com/library/courses/how-git-works/table-of-contents)

# Notes from "Git: The Big Picture"
## Shell or Terminal
- `$ cd <path-to/directory-name>` // change directory to move to another folder in the file system
- `$ less <filename>` // preview a file: use "f" to go forward (see more), "b" to go back and "q" to quit the preview
- `$ ls -a` // lists all files in a directory (including hidden)
- `$ ls -al` // lists all files in a directory with columns for permissions and date/time changed
- `$ man <any-command>` // manual for a command
    // type "q" to get out of the manual
- *arrow up* // moves through previous commands, starting with most recent
- `$ touch <filename>` // creates a file of <filename>
- `$ echo "<hello>" > <filename>` // creates a file of that name with the contents in quotes
- `$ tree` // if available, shows all files in a the current directory and below in a tree structure

## Git
### Creating a git repo locally
1. `$ git init` // creates a Git repository (repo)
1. Add and edit files to the directory
1. `$ git add .` // adds everything in that directory and all subdirectories to the repo's index
1. `$ git commit -m "Commit message"` // takes a snapshot of the directory and subdirectories add puts it in the repo with a commit number for accessing it later

### Making changes to a local repo
1. Add or edit files in directory with a .git file
1. `$ git status` // shows the status of the repo, including any files added or modified that have not been added to the repo index
1. `$ git add <filename|directory/|.>` // either one file or a whole directory, or everything in the current directory
1. `$ git commit -m "<Commit message>"` // takes a snapshot of the directory and subdirectories add puts it in the repo with a commit number for accessing it later
1. `$ git log` // displays the commit history (latest first)

### Comparing commits
- `$ git diff <older-commit-#> <newer-commit-#>` // only need to use some of the commit number to compare

### Traveling back and forth in time (and so much more)
- `$ git checkout <commit-#|branch-name>`

### Other commands
- `$ git <command> --help` // shows how the command can be called
- `$ git pull` // updates local repo with changes from default remote
- `$ git pull <remote-name>/<branch>` // updates local <branch> with remote changes from <remote-name>

### Open Source Workflow
1. Fork repository in <GitHub>
1. `$ git clone <your-fork-of-repository>` // locally
1. `$ cd <path-to-your-fork>` 
1. Work on code
1. `$ git add .` // from where the .git file is to add all files
1. `$ git commit -m "<some message>"`
1. `$ git push`
1. In GitHub, Make pull request on original repo with changes from fork

# Other notes
- Git tracks changes to source code (really is just tracks any changes to a directory and its subdirectories)
- Version control is not backup
- You can use branching and merging to have different versions of source code
- Primary reason to have version control is sharing repo with others
- Many other processes (testing, bugs, builds, compiles, deploys) can be run from changes, linked to commits
- The code repo is the center of the project
- Git is hard to learn but easy to use
- GitHub and Gitlab makes using Git easier
