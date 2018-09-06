# How-to-git
Hafpafs simple guide to simple git

![alt text](https://i.imgur.com/Aofvzhw.png "Git transport")

`git clone git@url-for-repository`

`git add file-you-changed`

`git commit -m "short explanaion of changes made"`

`git push`



When `git commit` doesn't like you and promts this:

```
*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"
```
Then run the two commands shown.
If it fails after, try check `git config --global -l` to see if you wrote correctly.


It is also possible to edit the config file in git with `git config --global --edit`


Also read: 
* https://blog.osteele.com/2008/05/my-git-workflow/#fnref:2
* https://media.pragprog.com/titles/tsgit/chap-005-extract.html
* https://stackoverflow.com/questions/14662526/why-git-is-not-allowing-me-to-commit-even-after-configuration#14662703

Markdown cheatsheet: https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet#lists
