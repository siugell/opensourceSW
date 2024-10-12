# Basic Git Usage

## Version Control and Collaboration
In software development, a version control system is essential for efficient collaboration.  
Using file copies for versioning can become complex and is difficult to manage.  
Git simplifies tracking changes and allows for systematic management.

## Data Storage Methods
1. **Change-based storage**: Only stores the modified parts of a file.
2. **Snapshot storage**: Saves the state of a file as a snapshot at specific points.

## Three States in Git
- **Modified**: The file has been changed.
- **Staged**: The file is ready to be committed.
- **Committed**: The file is stored in the local database.

## Installing and Configuring Git
- Installation links: [Windows](https://git-scm.com/download/win), [Mac](https://git-scm.com/download/mac)
- Git configuration file locations: System (`/etc/gitconfig`), User (`~/.config/git/config`), Local (`.git/gitconfig`)  
- Configuration priority is System < User < Local.

## Basic Git Commands
1. **Initialize a repository**: `$ git init`
2. **Check repository status**: `$ git status`
3. **Add a file (Staging)**: `$ git add [filename]`
4. **Commit**: `$ git commit -m "commit message"`
5. **Change branch name**: `$ git branch -M [branch name]`

## Other Useful Features
- **Ignore files**: Use a `.gitignore` file to exclude specific files from version control.
- **Unstage a file**: `$ git rm --cached [filename]`
- **Add all files**: `$ git add .`

--- 
