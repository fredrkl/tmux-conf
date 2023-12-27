# My Tmux configuration

Tmux, short for "terminal multiplexer", is a powerful command-line tool used primarily on Unix-like operating systems. This repository shows my tmux configuration.

## Setup

This repo is highly inspired by the [joseam-dev repo](https://github.com/josean-dev/dev-environment-files/blob/main/.tmux.conf).

Clone this repo and create a symlink to the configuration:

```
ln -s tmux-repo-path/.tmux.conf real-tmux-path/.tmux.conf
```

Run the following:

```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm 
```

When you start tmux, press ```prefix + I``` to install all the plugins.
