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
ctrl x (in some file manager)                 split screen horizontally (stack vertically) 
ctrl v (in some file manager)                 split screen vertically (stack horizontally)
ctrl (hjkl)                                   move between splits (VIM keybindings)
```
----------------------------------------------------------------------------------------------------------------

### vim panes
```
<Ctrl-w> s                                    split window horizontally
<Ctrl-w> v                                    split window vertically
<Ctrl-w> q                                    close window

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

