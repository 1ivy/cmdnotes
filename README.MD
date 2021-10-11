## Initial take off commands:

### Git:

🙃 `main` is the new `master` 🙃<br />
༼ つ ◕_◕ ༽つ

### ✨Update✨: 

##### ✨The following block was copied straight from the Master's Gold Mine Vault:✨

```shell
git init # Creates a new git repository in the current directory
git status # Show the repository status
git diff # Show the file differences in the working tree
git diff --staged # Show the file differences in staged files

git clone <remote-repository-address> # Clones the remote repository
git fetch # Download objects and refs
git fetch --all # Fetch all remotes
git pull <remote> <branch-name> # Update local with changes from remote
git pull # Update local with changes from origin (works after 'git pull origin master' once)
git pull --all # Updates local with all branches and changes from origin

git branch # List local branches
git branch -a # List all branches
git checkout -b <branch-name> # Create a new branch and switch to it
git branch <branch-name> # Create a new branch without switching to it
git checkout <branch-name> # Switch to a new branch
git checkout origin/<branch-name> # Switch to an upstream branch
git branch -m <new-branch-name> # Rename the current branch
git branch -m <old-branch-name> <new-branch-name> # Rename a branch
git merge <branch-name> # Merges the changes in <branch-name> into the current branch
git branch -d <branch-name> # Deletes a pushed or merged branch
git branch -D <branch-name> # Force delete a branch
git push <origin-or-remote-name> --delete <branch-name> # Delete a remote branch

git add . # Stage all changed files for commiting
git add <file-path> # Stage the file for commiting
git add <file-path>\* # Stage all the files in the directory for commiting
git reset # Undo the git add command for all files, no changes lost
git reset <file-path> # Undo the git add command for a single file, no changes lost
git commit -m "<message>" # Commit the staged files into the local repository
git commit --amend # Change the last commit message for local only
git reset --soft HEAD~1 # Undo the last commit locally preserving changes
git reset --hard HEAD~1 # Delete the last commit losing all modifications
git reset --hard HEAD # Delete all changes in the working tree
git reset --hard <commit-hash> # Deletes everything back to the previous commit
git push origin <branch-name> # Push the local repository changes up to the origin
git push -f origin <branch-name> # Force push the local repository changes up to the origin

git log # Show the commit logs
git log --oneline # Shows the commit logs with key and message only
git log <file-path> # Shows the commit logs for a single file

git checkout <file-path> # Resets a changed file back to the last commit state
git checkout <commit-hash> -- <file-path> # Resets a file back to a commit state
git checkout <commit-hash> # Switch the working tree to a previous commit
git checkout -b <branch-name> <commit-hash> # Create a new branch from an previous commit
git revert <commit-hash> # Adds a new commit at the HEAD set to a previous commit
git rm <file-name> # Remove a file from the working tree and from git
git rm --cached <file-name> # Remove a file from git without remove the local file

git tag # List all tags
git tag <tag-name> # Creates a lightweight tag to the current commit
git tag -a <tag-name> # Creates an annotated tag to the current commit
git push origin <tag-name> # Pushes a local tag to the origin
git push origin --tags # Pushes all local tags to the origin

git remote -v # List all remotes
git remote add <remote-alias> <remote-address> # Add a new remote
git remote rm <remote-alias> # Remove a remote
```

#### what Github says:

```shell
#### - new repo from cmd line:
git init
git add README.md
git commit -m "commit message"
git branch -M main
git remote add origin <origin>
git push -u origin main

#### - push an exiting repo from cmd line:
git remote add origin <origin>
git branch -M main
git push -u origin main
```

#### what also works

```shell
git push --set-upstream origin main
git push origin main

git branch #current branch
git branch -r #list remost branch
git branch -a #list all local and remote branch
git checkout -b <hi> #create a new branch called hi

git add . #add all changes

rm -rf .git #remove git from a directory after a wrong git init 😹

git diff #show the file differences
git status #when in doubt, git status 🧠
```


### Vim:
* 🔗[Learn Vim blog post](https://danielmiessler.com/study/vim/)
* 🔗[Learn Vim Game](https://vim-adventures.com/)
* 🔗[Learn Vim book on Github](https://github.com/iggredible/Learn-Vim)

```shell
vi README.md #create a file called README.md and open it in the magical land of Vim

i #insert mode, start editing file
ESC #get out of current mode (insert/command)
:wq #save changes and exit vim
:q! #quit without saving changes

j #down ↓ 👇
k #up ↑ 👆
h #left ← 👈 
l #right → 👉

```

### Linux:

> ❤ find package => install package❤

* 🔗[Debian Docs](https://www.debian.org/doc/manuals/debian-reference/pr01.en.html)
* 🔗[tldr](https://tldr.ostera.io/)

```shell
code . #open in VSCode
CTRL ~ #open terminal in VSCode
CTRL c #kill it now, make it stop

sudo apt update && sudo apt upgrade

sudo apt search ssh-keygen #search for ssh packages
sudo apt install openssh-client


find -name "wow*"
find -name "*wow*" -exec mv -t ./<file path here>/ {} + #find file name cantaining "wow" and move them to another directory

```

#### VSCode

```shell
CTRL SHIFT p -> wordWrap # turn on text wrap in VSCode
CTRL SHIFT p -> autosave # turn on auto savce in VSCode
```
