# Alias for git commands

```git
[user]
  email = your-email@your-domain
  name = Your name here
[core]
  editor = code --wait
[alias]
  c = !git add --all && git commit -m
  s = !git status -s
  l = !git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn %C(green)%cr'
  a = !git add --all && git commit --amend --no-edit
```
