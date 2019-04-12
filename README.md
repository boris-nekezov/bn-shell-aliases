# dotfiles
Containing dotfiles with aliases and shorcuts

## List of aliases for git bash

```sh
# terminal
alias ll='ls -la'
alias ..='cd ..'

# git
alias g='git'
alias gs='git status'
alias ga='git add'
alias gaa='git add -A'
alias gc='git commit -m'
alias gcc='git commit -m "Update application"'
alias gd='git diff'

alias gp='git push'
alias gpom='git push origin master'
alias gpod='git push origin develop'

alias gacp='gaa && gcc && gp'

alias gpll='git pull'
alias gpllom='git pull origin master'
alias gpllod='git pull origin develop'

alias gb='git branch'

alias gch='git checkout'
alias gchm='git checkout master'
alias gchd='git checkout develop'
alias gchb='git checkout -b'

alias gr='git reset'

alias grm='git rm'
alias grmr='git rm -r'
alias grmf='git rm -f'
alias grmrf='git rm -rf'

alias gst='git stash'
alias gsta='git stash apply'

alias gl='git log'
alias glol='git log --oneline'

# vue
alias vue='winpty vue.cmd'
```