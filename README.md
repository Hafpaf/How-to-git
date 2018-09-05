# How-to-git
Hafpafs simple guide to simple git

![alt text](https://i.imgur.com/Aofvzhw.png "Git transport")

git clone url-for-repository

git add file-changed

git commit -m "changes made"

git push



When `git commit` doesn't like you and promts this:

```*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"
```
Then run the two commands shown.
If it fails after, try check `git config --global -l` to see if you wrote correctly.


It is also possible to edit the config file in git with `git config --global --edit`
