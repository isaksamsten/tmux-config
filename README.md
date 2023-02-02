# Isak Samsten's tmux config

## Installation

Clone the repository

    git clone https://github.com/isaksamsten/tmux-config.git ~/.config/tmux

Install the plugin manager

    git clone https://github.com/tmux-plugins/tpm ~/.config/tmux/plugins/tpm

Start tmux and issue `<C-b>I` to install the plugins

### Fixes for MacOS

The by default MacOS does not have `tmux-256color` installed.

To install it

    curl -LO https://invisible-island.net/datafiles/current/terminfo.src.gz && gunzip terminfo.src.gz
    /usr/bin/tic -xe tmux-256color terminfo.src

[Source](https://gist.github.com/bbqtd/a4ac060d6f6b9ea6fe3aabe735aa9d95)
