# My Alias for bash terminal

## Commands for open alias list in notepad

```shell
notepad ~/.bashrc
```

## Alias List

```shell
alias ga='git add'
alias gaa='git add .'
alias gap='git add --patch'
alias gc='git commit --verbose'
alias gca='git commit -a --verbose'
alias gcm='git commit -m'
alias gcam='git commit -a -m'
alias gpm="git checkout main && git pull"

alias gst='git status'
alias gco='git checkout'
alias gcob='git checkout -b'

alias gl='git log'
alias gp='git push origin -u HEAD'
alias gfp='git fetch --prune'

alias gdelall='git branch | grep -v "main" | xargs git branch -D'

alias nrd='npm run dev'

alias ys='yarn start'
alias y='yarn'

alias c='code .'
alias cl='clear'

alias gh='history|grep'

alias cg='cd D:/Projects/F1'

alias s='start'
alias sd='start docker'
```
