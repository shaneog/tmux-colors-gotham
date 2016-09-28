# Gotham color theme for tmux

A tmux theme based on [vim-gotham](https://github.com/whatyouhide/vim-gotham).

## Installation

Append the content of e.g. `tmuxcolors-gotham.conf` to the end of your tmux config.

```shell
cat tmuxcolors-gotham.conf >> ~/.tmux.conf
```

In most cases, you have to force tmux to assume the terminal supports 256 colours.
For this, start tmux with `tmux -2`.

### Installation with [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm)

Add the plugin to the list of TPM plugins in your `.tmux.conf`:

    set -g @plugin 'shaneog/tmux-colors-gotham'

Hit `prefix + I` to fetch the plugin and source it. The plugin should now be working.
