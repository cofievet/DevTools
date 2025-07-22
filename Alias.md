# My Alias for bash terminal

## Commands for open alias list in notepad

```shell
notepad ~/.bashrc
```

## Alias List

```shell
alias ga='git add .'
alias gap='git add --patch'
alias gcm='git commit -m'
alias gc='git checkout'
alias gcb='git checkout'
alias gcob='git checkout -b'
alias gs='git status'
alias gps='git push origin -u HEAD'
alias gp='git pull'

alias gpm="git checkout master && git pull"
alias gpv1="git checkout releases/v1 && git pull"
alias gdelall='git branch | grep -v "master" | grep -v "releases/v1" | xargs git branch -D'

__git_complete gco _git_checkout

alias gl='git log'
alias gfp='git fetch --prune'
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
