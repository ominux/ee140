# EE140 Project
Leticia Ibarra, Vikram Iyer, Alyssa Zhou

## Directory Structure
This project is a Cadence library which has all of the circuits for individual blocks. To import append a line to `cds.lib` in `~/ee140`.

Each cell is a sub-folder in this directory.  

## Setup
1. In the `ee140` directory type `git clone https://github.com/viyer/ee140.git` 
2. Open `cds.lib` and make sure that this folder is included in the file.
3. Follow the workflow below.

## Git Workflow 
1. Before starting Cadence, run `git pull` 
This will download the most recent version of the project from the remote repository.

Whenever you are ready to save something and upload it to the remote repository:
2. Go up to the top level directory (e.g. project) and type `git add .`
3. Run `git commit`. Type a brief message explaining your changes and save the text file. This will also show a full list of the files you have changed.
4. Run `git push origin master` to upload your changes to the remote repository.

### Removing Cadence lock files
Run `./remove_lock_files`
Git is set up not to keep track of the lock files or upload them to the remote repository, but you may still have local versions of Cadence lock files. If you ever get weird issues not being able to open files try running this.

More [information/a more detailed introduction to git](http://rogerdudler.github.io/git-guide/) to
using git. The most common commands are also listed below for convenience.

This
[cheatsheet](https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf)
has a more extensive list of common commands.
