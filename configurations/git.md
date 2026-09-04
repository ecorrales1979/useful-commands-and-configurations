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
  ac = !git add --all && git commit -m
  c = !git commit -m
  a = !git add --all && git commit --amend --no-edit
  s = !git status -sb
  l = !git --no-pager log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn %C(green)%cr'
  plo = !git pull origin $(git branch --show-current)
  pso = !git push origin $(git branch --show-current)
  count = !git shortlog -s --grep
```
