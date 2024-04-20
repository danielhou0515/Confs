# Confs

## Table of Contents
- [Confs](#confs)
  - [Table of Contents](#table-of-contents)
  - [tmux shortcuts](#tmux-shortcuts)
    - [tmux sessions](#tmux-sessions)
    - [tmux windows](#tmux-windows)
    - [in tmux](#in-tmux)
  - [nvim shortcuts](#nvim-shortcuts)
    - [tabs management](#tabs-management)
    - [vim panes](#vim-panes)
    - [navigation](#navigation)
    - [editing](#editing)
    - [diagnostics](#diagnostics)
    - [substition](#substition)
  - [harpoon shortcuts](#harpoon-shortcuts)
    - [harpoon commands](#harpoon-commands)
  - [telescope shortcuts](#telescope-shortcuts)
    - [telescope commands](#telescope-commands)
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
ctrl s x                                        close panel
ctrl s z                                        toggle panel full screen
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
### tabs management
```
ctrl t (in file manager or normal mode)         open new tab
gt                                              move to next tab to right
gT                                              move to next tab to left

ctrl w                                          close tab
ctrl (hjkl)                                     move between splits (VIM keybindings)
```
----------------------------------------------------------------------------------------------------------------

### vim panes
```
<Ctrl-w> s                                      split window horizontally
<Ctrl-w> v                                      split window vertically
<Ctrl-w> q                                      close window
```
----------------------------------------------------------------------------------------------------------------

### navigation
```
zz, zt, zb                                      put line as center, top, bottom
ctrl ]                                          go to tag
ctrl o                                          go back
ctrl i                                          go forward

m[char]                                         mark cursor location as [char]
'[char]                                         go to marked cursor location

{ or }                                          go to next/prev blank line
* or #                                          go to next/prev word under cursor

f/F [char]                                      go to next/prev [char] in line
t/T [char]                                      go to next/prev [char] in line before [char]
```
----------------------------------------------------------------------------------------------------------------

### editing
```
v                                               characterwise visual mode
V                                               linewise visual mode
O                                               add line above

]p                                              paste with correct indentation
.                                               repeat last command
v/c/d ip                                        highlight/change/delete inside _ (paragraph, words, quotes, etc.) pos does not matter
v/c/d ap                                        highlight/change/delete around _ (paragraph, words, quotes, etc.) pos does not matter
v/c/d t/f [char]                                highlight/change/delete until/forward _ (words, quotes, etc.)

=ap                                             auto indent paragraph

o                                               switch highlight position (visual mode)
```
----------------------------------------------------------------------------------------------------------------

### diagnostics
```
space e                                         open diagnostics list on line
space q                                         open all diagnostics
[/] d                                           go to next/prev diagnostic
```
----------------------------------------------------------------------------------------------------------------

### substitution
```
% makes in file
/g makes global (within a scope)
/c makes confirmation

:s/foo/bar                                      replace first foo with bar in line
:s/foo/bar/g                                    replace all foo with bar in line
:#,#s/foo/bar/g                                 replace all foo with bar in range of (#, #)
:%s/foo/bar/g                                   replace all foo with bar in file
:%s/foo/bar/gc                                  replace all foo with bar in line with confirmation
```
----------------------------------------------------------------------------------------------------------------
## harpoon shortcuts
### harpoon commands
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

## telescope shortcuts
### telescope commands
```
space ft                                        toggle file tree
space gf                                        search files in dir (just git files)
space sf                                        search files in dir (hidden files)
space sg                                        search by grep in dir
space sG                                        search by grep in dir (git dir)
space ut                                        open undo tree
space s/                                        search in open files
space sd                                        search diagnostics

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

ctrl x (in some file manager)                   split screen horizontally (stack vertically) 
ctrl v (in some file manager)                   split screen vertically (stack horizontally)
```
----------------------------------------------------------------------------------------------------------------
