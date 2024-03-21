# Confs

## tmux shortcuts
### tmux sessions
* tmux -> start new session
* ctrl s $ -> rename session
* tmux new -s [name] -> start new session with name
* tmux a -> attach to last session
* tmux a -t [name] -> attach to session with name
* tmux ls -> list sessions
* tmux kill-session -t [name] -> kill session with name
* ctrl s s -> list sessions
* ctrl s d -> detach session

### tmux windows
* ctrl s c -> create new window
* ctrl s n/p -> go to next/prev window
* ctrl s -> rename the current window
* ctrl s w -> list windows
* ctrl s & -> kill window

### in tmux
* ctrl (hjkl) -> move between panels (VIM keybindings)
* ctrl s " -> open panel (stack vertically)
* ctrl s % -> open panel (stack horizontally)
* ctrl s x -> close panel
* ctrl s [ -> scroll
* q -> quit scroll
* ctrl m -> toggle mouse mode (iterm)

## nvim shortcuts
### plugins
* space ft -> toggle file tree
* space sf -> search files in dir

* space space -> search files in buffer
* space / -> search words in current buffer
* space d s -> search for symbols in document
* space w s -> search for symbols in buffer

* space w a -> add folder in buffer
* space w r -> remove folder from buffer
* space w l -> list folders in buffer

* gd/gD -> go to definition/declaration of thing under cursor
* gr -> go to references of thing under cursor
* leader D -> go to definition of type
* K -> show documentation (shorter) of thing under cursor
* ctrl k -> show documentation (longer) of thing under cursor


## tabs management
* ctrl t (in some file manager or just normal mode) -> open new tab
* gt -> move to next tab to right
* gT -> move to next tab to left
* n gt -> move to nth tab

* ctrl w -> close tab
* ctrl x (in some file manager) -> split screen horizontally (stack vertically) 
* ctrl v (in some file manager) -> split screen vertically (stack horizontally)
* ctrl (hjkl) -> move between splits (VIM keybindings)


### modes
ctrl o (in insert mode) -> execute one command in command mode and go back to insert mode


### saving/closing
* XX -> save file (without close)

### navigation
* zz, zt, zb -> put line as center, top, bottom
* ctrl ] -> go to tag
* ctrl o -> go back

* m[char] -> mark cursor location as [char]
* '[char] -> go to marked cursor location

* { or } -> go to next/prev blank line
* * or # -> go to next/prev word under cursor

### editing
* v -> characterwise visual mode
* V -> linewise visual mode
* O -> add line above

* ]p -> paste with correct indentation
* %/foo/bar/g -> replace all foo with bar
* . -> repeat last command

