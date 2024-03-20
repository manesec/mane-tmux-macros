# mane-tmux-macros
story my macros

Requirement: [tmux-command-macros](https://github.com/manesec/tmux-command-macros)

## Usage

```bash
git clone https://github.com/manesec/tmux-command-macros.git ~/mane-tmux-macros

# in ~/.tmux.conf

# setup tmux-text-macros
set -g @tcm-window-mode vertical
set -g @tcm-marod-dir ~/mane-tmux-macros                          
run-shell ~/.tmux/plugins/tmux-command-macros/tmux-command-macros.tmux  


# finally 
tmux source ~/.tmux.conf
```

## License

MIT