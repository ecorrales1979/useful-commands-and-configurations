# Alias for git commands

```git
[user]
  email = your-email@your-domain
  name = Your name here
[core]
  editor = code --wait
[push]
  followTags = true
[alias]
  c = !git add --all && git commit -m
  s = !git status -s
  l = !git --no-pager log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn %C(green)%cr'
  a = !git add --all && git commit --amend --no-edit
  count = !git shortlog -s --grep
```
