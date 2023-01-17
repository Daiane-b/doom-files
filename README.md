# Shortcusts

## General navigation and edition

| shortcut | description |
| ---------| ------------|
| `space w h`| Navigate to window left |
| `space w l`| Navigate to window right |
| `v %` | Select the current function |
| `u` | Undo
| `Control r`| Redo

# Emacs DOOM

## Terminal helpers
`zhrc`:
````
alias ec="emacsclient -nw"
alias ekill="emacsclient -e '(kill-emacs)'"
alias edaemon="emacs --daemon"
alias erestart="ekill && edaemon"```
