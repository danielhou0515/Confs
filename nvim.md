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
%/foo/bar/g                                     replace all foo with bar
.                                               repeat last command
di'                                             delete inside single quotes (ex)
ci'                                             change inside single quotes (ex)
da'                                             delete around single quotes (ex)
```
----------------------------------------------------------------------------------------------------------------

