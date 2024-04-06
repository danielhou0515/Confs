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
