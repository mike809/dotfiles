alias gb='git branch'
alias gs='git status'
alias ga='git add'
alias gbn="git branch | awk '/\*/ {print $2}'"
alias gpb="git push origin (gbn)"
alias gpull="git pull origin (gbn)"
alias gco='git commit'
alias gf='git fetch'


branch (){
  git branch | awk '/*$1*/ {print $2}'
}
