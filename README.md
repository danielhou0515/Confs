# Confs

## Table of Contents
- [Confs](#confs)
  - [Table of Contents](#table-of-contents)
  - [tmux shortcuts](#tmux-shortcuts)
    - [tmux sessions](#tmux-sessions)
    - [tmux windows](#tmux-windows)
    - [in tmux](#in-tmux)
  - [nvim shortcuts](#nvim-shortcuts)
    - [plugins](#plugins)
    - [tabs management](#tabs-management)
    - [modes](#modes)
    - [saving/closing](#savingclosing)
    - [navigation](#navigation)
    - [editing](#editing)
  - [harpoon shortcuts](#harpoon-shortcuts)
    - [harpoon commands](#harpoon-commands)
## tmux shortcuts
### tmux sessions
```
tmux                                            start new session
tmux new -s [name]                              start new session with name
tmux a                                          attach to last session
tmux a -t [name]                                attach to named session
tmux ls                                         list sessions
tmux kill-session -t [name]                     kill session with name
ctrl s s                                        list sessions
ctrl s d                                        detach session
ctrl s $                                        rename session
```
----------------------------------------------------------------------------------------------------------------

### tmux windows
```
ctrl s c                                        create new window
ctrl s ,                                        rename cur window
ctrl s n/p                                      go to next/prev window
ctrl s w                                        list windows
ctrl s &                                        kill window
```
----------------------------------------------------------------------------------------------------------------

### tmux panel
```
ctrl (hjkl)                                     move between panels (VIM keybindings)
ctrl s "                                        open panel (stack vertically)
ctrl s %                                        open panel (stack horizontally)
ctrl s x                                      close panel
```
----------------------------------------------------------------------------------------------------------------

### in tmux
```
ctrl s [                                        scroll
q                                               quit scroll
ctrl m                                          toggle mouse mode (iterm)
```
----------------------------------------------------------------------------------------------------------------

## nvim shortcuts
### plugins
```
space ft                                        toggle file tree
space sf                                        search files in dir

space space                                     search files in buffer
space /                                         search words in current buffer
space d s                                       search for symbols in document
space w s                                       search for symbols in buffer

space w a                                       add folder in buffer
space w r                                       remove folder from buffer
space w l                                       list folders in buffer

gd/gD                                           go to definition/declaration of thing under cursor
gr                                              go to references of thing under cursor
leader D                                        go to definition of type
K                                               show documentation (shorter) of thing under cursor
ctrl k                                          show documentation (longer) of thing under cursor
```
----------------------------------------------------------------------------------------------------------------


### tabs management
```
ctrl t (in file manager or normal mode)       open new tab
gt                                            move to next tab to right
gT                                            move to next tab to left
n gt                                          move to nth tab

ctrl w                                        close tab
```
----------------------------------------------------------------------------------------------------------------

### vim panes
```
<Ctrl-w> s                                    split window horizontally
<Ctrl-w> v                                    split window vertically
<Ctrl-w> q                                    close window

ctrl x (in some file manager)                 split screen horizontally (stack vertically) 
ctrl v (in some file manager)                 split screen vertically (stack horizontally)
ctrl (hjkl)                                   move between splits (VIM keybindings)

<Ctrl-w> -                                    decrease height of split by 1 line
<Ctrl-w> +                                    increase height of split by 1 line
<Ctrl-w> >                                    increase width of split by 1 line
<Ctrl-w> <                                    decrease width of split by one line
ctrl w =                                      make all splits equal size
```
----------------------------------------------------------------------------------------------------------------

### modes
```
ctrl o (in insert mode)                         execute one command in command mode and go back to insert mode
```
----------------------------------------------------------------------------------------------------------------

### saving/closing
```
XX                                            save file (without close)
```
----------------------------------------------------------------------------------------------------------------

### navigation
```
zz, zt, zb                                    put line as center, top, bottom
ctrl ]                                        go to tag
ctrl o                                        go back

m[char]                                       mark cursor location as [char]
'[char]                                       go to marked cursor location

{ or }                                        go to next/prev blank line
* or #                                        go to next/prev word under cursor

f/F [char]                                    go to next/prev [char] in line
t/T [char]                                    go to next/prev [char] in line before [char]
```
----------------------------------------------------------------------------------------------------------------

### editing
```
v                                             characterwise visual mode
V                                             linewise visual mode
O                                             add line above

]p                                            paste with correct indentation
%/foo/bar/g                                   replace all foo with bar
.                                             repeat last command
di'                                           delete inside single quotes (ex)
ci'                                           change inside single quotes (ex)
da'                                           delete around single quotes (ex)
```
----------------------------------------------------------------------------------------------------------------

## harpoon shortcuts
### harpoon-commands
```
space h m                                       open harpoon menu
space h a                                       harpoon file
space h                                         go to file 1
space h                                         go to file 2
space h                                         go to file 3
space h                                         go to file 4
space n/N                                       go to next/prev file
```
----------------------------------------------------------------------------------------------------------------

