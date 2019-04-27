----------------------------------------
**Command**--------------|--- **description**--------   
**=================|=====================**

## Installation
- *brew install tmux* ------> installs tmux via HomeBrew of OSX
- *tmux -V* -------> to check the tmux version
###### the basics  ##
- *tmux* ------> Starts new tmux session
- *exit* ------> to exit the tumx session
- *tmux new -s session-name* ------> starts a new sessionw and named it 'sesion-name'

**Note: for all commands you have to first press *ctrl+b* to inter to the command mode**


 # Working on Panes  ##
 ### spliting
- *ctrl + b + %* ---->  split the pan vertically
- *ctrl + b + "*  ----> split the  horizontally

### Resizing Panes
- *ctrl + b + : resize-pane -D* ---> Resizes the current pane down
- *ctrl + b + :resize-pane -D 10* ---> Resizes the current pane down by 10 cells
- *ctrl + b + : resize-pane -U* ---> Resizes the current pane Up
- *ctrl + b + :resize-pane -U 10* ---> Resizes the current pane Up by 10 cells
- *ctrl + b + :resize-pane -L* ---> Resizes the current pane to left
- *ctrl + b + :resize-pane -L 10* ---> Resizes the current pane left by 10 cells
- *ctrl + b + :resize-pane -R* ---> Resizes the current pane to right
- *ctrl + b + :resize-pane -R 10* ---> Resizes the current pane right by 10 cells
