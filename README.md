# Learning Git and GitHub
**_NOTE:_** This repository is for learning Git and GitHub. It will be chaotic and messy, but it's for learning purposes

## Git commands (not all of them, only the ones that are interesting for me)

### Commits
- `git commit --amend`: Change the last commit message and modify the files(add the changes to the stagging area before running the command).

### Git config
- `git config --global user.name "Your Name"`: Set the name that will be attached to your commits.
- `git config --global user.email "Your Email"`: Set the email that will be attached to your commits.
- (use in linux) `git config --global core.autocrlf input`: Set the line endings to LF.
- (use in windows) `git config --global core.autocrlf true`: Set the line endings to CRLF.
- `git config --global core.editor "Your Editor"`: Set the default editor for git.
- `git config --global --list`: List all the configurations for git.
- `git config --global commit.template ~/.gitmessage.txt`: Set a template for the commit message.
- `git config --global init.defaultBranch <branch name>`: Set the default branch name for new repositories.
