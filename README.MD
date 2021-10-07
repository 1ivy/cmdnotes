## Initial take off commands:

### Git:

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

