# tmux.config

PREFIX Key is Ctrl+z
Config File : ~/.tmux.conf
See config folder in this repo for the config and key bindings

## Open new tab
<PREFIX> + c

### Switch from one tab to the other
<PREFIX> + <tab number>

### Rename a Tab
<PREFIX> + ,

### Split Pane vertically
<PREFIX> + |

### Split Pane Horizontally
<PREFIX> + -

### toggle Zoom on a pane
<PREFIX> + z

### Navigation between panes
alt + arrow keys

=== 

## Sessions

### Show running sessions
tmux ls

### Detach Session (from inside tmux)
<PREFIX> + d

### Resume session
tmux attach -t <session name or number>

### Rename an existing session
tmux rename-session -t <number or old name> <name>

### Open tmux with a named session
tmux new -s <name>

### Killing sessions
tmux kill-session -t <name or number>

===
