# How to git

**A guide for Git containing the most essential commands and how to use them.**

## The Basic commands

#### 1. Install git if you haven't already.
  * Ubuntu: `sudo apt-get install git`
  * Arch: `sudo pacman -S git`
  * Windows: https://git-scm.com/
  * Or just use your prefered package installer

#### 2. Create a local copy of the repository

`git clone git@url-for-repository`

#### 3. You are now ready to get hacking with the code. Changes made to the files can be added to the next commit with.

`git add file-you-changed`

#### 4. A **commit** means to record the changes made withing the local repository on you machine and you can easily make more commits before pushing.

`git commit -m "short explanaion of changes made"`

#### 5. Upload the the changes made to your local repository the the repository server.

`git push`

Congratulaions, you have now learned the 4 most essential commands og Git.

### Other commands

* Use `git status` to se all the changes made before the last commit

### A wonderfull explanation about different how Git works
![alt text](https://i.imgur.com/Aofvzhw.png "Git transport")



## Git Commit troubleshooting

When `git commit` doesn't like you and promts this:

```
*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"
```
Then run the two commands shown.

Try to run the commit again, if it fails again and promts the same message, use `git config --global -l` to see if you wrote correctly.


It is also possible to edit the config file in git with `git config --global --edit`


Also read: 
* https://blog.osteele.com/2008/05/my-git-workflow/
* https://media.pragprog.com/titles/tsgit/chap-005-extract.html
* https://stackoverflow.com/questions/14662526/why-git-is-not-allowing-me-to-commit-even-after-configuration

Markdown cheatsheet: https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet
