# How to git

**A guide for Git containing the most essential commands and how to use them.**

#### 1. Install git if you haven't already.
  * Ubuntu: `sudo apt-get install git`
  * Arch: `sudo pacman -S git`
  * Windows: https://git-scm.com/
  * Or just use your prefered package installer

## The Basic commands

#### 1. Create a local copy of the repository

`git clone git@url-for-repository`

#### 2. You are now ready to get hacking with the code. Changes made to the files can be added to the next commit with.

`git add file-you-changed`

Note: it is possible to *add* a file or a folder

#### 3. A **commit** means to record the changes made withing the local repository on you machine and you can easily make more commits before pushing.

`git commit -m "short explanaion of changes made"`

#### 4. Upload the the changes made to your local repository the the repository server.

`git push`

The changes you made has now been uploaded.

#### 5. To update your local repository in case you are collaborating with others.

`git fetch`

**Congratulaions, you have now learned the 5 most essential commands og Git.**

### Other commands

* Use `git status` to se all the changes made before the last commit

### A wonderfull explanation about how Git works
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

## Pull Request
When colaborating with others, it can be a good idea to create a new branch for major edits in your code while also being able to merge new edits from your colaborators.
#### 1. Create new branch
```git
git checkout -b <branch_name>`
```
#### 2. Write your code.

#### 3. Switch branch
```git
git checkout master
```
or push branch to remote

```git
git push -u origin <branch>
```

## Rename Branch
### Rename a branch
```git
git branch -m <oldname> <newname>
```

### Rename current branch
```git
git branch -m <newname>
```


# Ressources 
* https://blog.osteele.com/2008/05/my-git-workflow/
* https://media.pragprog.com/titles/tsgit/chap-005-extract.html
* https://stackoverflow.com/questions/14662526/why-git-is-not-allowing-me-to-commit-even-after-configuration

Markdown cheatsheet: https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet


## Sources used
* [Push local branch](http://stackoverflow.com/questions/2765421/ddg#6232535)
* [Rename local branch](http://stackoverflow.com/questions/6591213/ddg#6591218)
