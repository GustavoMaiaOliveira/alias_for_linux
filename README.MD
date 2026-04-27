<div align="center">

  <img src="\.github\Alias_Linux.png" alt="Logo" height="200">
  <h1 align="center"><strong>Alias for Linux</strong></h1>
  <p align="center">
	  This repository will help you for save yout time for type the same commands many times.<br> Here it constains <b>Git/GitHub</b> alias, <b>Linux OS</b> alias and more.
  </p>

</div>

<br />

  <!-- Badges -->
<div align="center">
  
  [![Linux][linux-badge]][linux]

</div>

# 🚀 Technologies

This project uses only text for paste in your ~/.bashrc:

### 📄 Files

- `alternative-alias` - File for you copy the text
- `README` - Contains commands and explain that there makes

### ⚡ Scripts

<b>Git/GitHub alias</b>

g: Shortcut for Git (git)
gi: Initialize a new Git repository (git init)
ga: Stage all changes (git add .)
gc: Commit with a message (git commit -m)
gs: Show current status of repo (git status)
gr: Show remote repositories (git remote -v)
gp: Push changes to remote (git push)
gcl: Clone a repository (git clone)
gpl: Pull latest changes from remote (git pull)
gl: Show commit history (git log)
glo: Show compact commit history (git log --oneline)
gc-: Undo last commit, keeping changes staged (git reset --soft HEAD~1)
gb: List or manage branches (git branch)
gbd: Delete branch forcefully (git branch -D)
gsw: Switch branches (git switch)
gst: Stash current changes (git stash)
gstpo: Apply last stash and remove it (git stash pop)
gch: Switch branches or restore files (git checkout)
gchb: Create and switch to new branch (git checkout -b)
gf: Fetch updates from remote (git fetch)

<b>npm alias</b>

n: Shortcut for npm (npm)
nini: Initialize a project (npm init)
nins: Install dependencies (npm install)
ninsf: Force install dependencies (npm install --force)
nuns: Uninstall package (npm uninstall)
nr: Run script (npm run)
nrd: Run dev script (npm run dev)

<b>Docker alias</b>

du: Start containers in background (docker compose up -d)
dp: List running containers (docker ps)
dpa: List all containers (docker ps -a)
ds: Stop container (docker stop)
dsa: Stop all containers (docker stop $(docker ps -a -q))
dr: Remove container (docker rm)
dra: Remove all containers (docker rm $(docker ps -a -q))

<b>VS Code alias</b>

c.: Open current folder in VS Code (code .)

<b>Linux / System alias</b>

c: Clear terminal (clear)
all: Open and reload bash config (nano ~/.bashrc && source ~/.bashrc)
sall: Reload bash config (source ~/.bashrc)

<b>Optional alias</b>

clj: Shortcut for running Clojure (clojure)

# 👨‍💻 How To Use

For use this alias, you'll need to have Linux OS installed on your computer. From your command line:

```bash
# Copy the alias
$ Open this link https://github.com/GustavoMaiaOliveira/alias_for_linux/blob/main/alternative-alias and copy the all content

# Open your Terminal, then go to ~/.bashrc
$ nano ~/.bashrc

# Paste this content before the end of file
$ Ctrl + Shift + V

# Save the file
$ Ctrl + O
$ Enter
$ Ctrl + X

# Reload the changes
$ source ~/.bashrc
```

## Author

| [<img src="https://avatars.githubusercontent.com/u/161539603?s=400&u=4e1355b2c475c870a92d5453f7cb32560478f40e&v=4"><br><sub>Gustavo Maia Oliveira</sub>](https://github.com/GustavoMaiaOliveira) |
| :---------------------------------------------------------------------------------------------------------------------------------------: |
|                                       [Linkedin](https://www.linkedin.com/in/gustavomaiaoliveira/)                                        |

[linux-badge]: https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black
[linux]: https://www.kernel.org/
