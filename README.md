# tmux-conf
A friendly and lightweight customized tmux configuration file for tmux beginners, including basic frequently-used hotkeys.

Many thanks to Ham Vocke's great article (See References).
## Tmux Guide

### Basic use
- C-b
- Pane: 
	- C-b %
	- C-b "
	- C-b left/right/up/down
	- C-d / exit
- Window
	- C-b c
	- C-b p/n
	- C-b number
- Session
	- tmux ls
	- tmux attach -t name
	- tmux new -s name
	- tmux rename-session -t name1 name2

### Moving on
- C-b ?
- C-b z and C-b z : make a pane to full screen
- C-b C-<arrow key> : resize pane
- C-b , : rename the current window

### References:
- http://www.hamvocke.com/blog/a-quick-and-easy-guide-to-tmux/
- http://www.hamvocke.com/blog/a-guide-to-customizing-your-tmux-conf/


