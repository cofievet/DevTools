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
alias gcam='git add . && git commit -a -m'
alias gl='git log'

alias gp='git push origin -u HEAD'

alias gst='git status'
alias gco='git checkout'
__git_complete gco _git_checkout

alias gcob='git checkout -b'

alias gfp='git fetch --prune'

alias gdelall='git fetch --prune && git branch | grep -v "main" | xargs git branch -D'
alias gpm="git checkout main && git pull"

alias grsth='git reset HEAD~'

alias nrd='npm run dev'

alias ys='yarn start'
alias y='yarn'

alias c='code .'
alias cl='clear'

alias gh='history|grep'

alias cg='cd D:/Projects/F1'

alias wgua='winget upgrade --all'
alias tlc='telepresence connect'

alias s='start'
alias sd='start docker'

alias dsac='docker stop $(docker ps -a -q)'
alias drmac='docker rm $(docker ps -a -q)'
alias drmai='docker rmi $(docker images -q)'
alias dcud='docker-compose up -d'

```
