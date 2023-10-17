# Shortcusts

## General navigation and edition

| shortcut | description |
| ---------| ------------|
| `SPC w h`| Navigate to window left |
| `SPC w l`| Navigate to window right |
| `SPC f p`| Access your doom's config files |
| `SPC g o o`| Open current file on Github, if text is selected, open the line |
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
| `:s/word-to-be-replaced/word-to-replace/ press ENTER`| Select with `v` and replace word to another word |
| `v a "`| Select around `"` including `"`|
| `v i "`| Select inside `"` not including `"`|

# Emacs DOOM

Doom uses `evil-mode` [package](https://github.com/emacs-evil/evil), it emaultes the main features of Vim
[Official doc](https://github.com/doomemacs/doomemacs/blob/master/docs/index.org)

| shortcut | description |
| ---------| ------------|
| `doom sync`| This synchronizes your config with Doom Emacs |

# Lein
After add some dependency run `lein deps` to update project

## Terminal helpers
`zhrc`:
````
alias ec="emacsclient -nw"
alias ekill="emacsclient -e '(kill-emacs)'"
alias edaemon="emacs --daemon"
alias erestart="ekill && edaemon"```
