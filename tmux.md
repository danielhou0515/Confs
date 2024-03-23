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

