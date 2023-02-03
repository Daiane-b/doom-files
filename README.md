# Shortcusts

## General navigation and edition

| shortcut | description |
| ---------| ------------|
| `SPC w h`| Navigate to window left |
| `SPC w l`| Navigate to window right |
| `v %` | Select the current function |
| `u` | Undo
| `Control r`| Redo |
| `v t (`| Select until ( |
| `y a (`| Copy inside () (use `d` to cut) |
| `:e TAB file`| Search for `file`, if not exists, it creates |
| `, e e`| Eval current line |
| `, e b`| Eval current buffer (eval after file modification) |
| `, r b`| Show repl window |
| `SPC p p`| Open project |
| `option 1`| Change to frame 1 |
| `, r l`| Load file in repl |
| `SPC SPC`| Load file in project |
| `SPC /`| Load something in project |
| `SPC f D`| Delete file |

# Emacs DOOM

# Lein
After add some dependency run `lein deps` to update project

## Terminal helpers
`zhrc`:
````
alias ec="emacsclient -nw"
alias ekill="emacsclient -e '(kill-emacs)'"
alias edaemon="emacs --daemon"
alias erestart="ekill && edaemon"```
