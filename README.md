# Shortcusts

## General navigation and edition

| shortcut | description |
| ---------| ------------|
| `space w h`| Navigate to window left |
| `space w l`| Navigate to window right |
| `v %` | Select the current function |
| `u` | Undo
| `Control r`| Redo |
| `v t (`| Select until ( |
| `y a (`| Copy inside () (use `d` to cut) |
| `:e TAB file`| Search for `file`, if not exists, it creates |
| `, e e`| Eval current line |


# Emacs DOOM

## Terminal helpers
`zhrc`:
````
alias ec="emacsclient -nw"
alias ekill="emacsclient -e '(kill-emacs)'"
alias edaemon="emacs --daemon"
alias erestart="ekill && edaemon"```
