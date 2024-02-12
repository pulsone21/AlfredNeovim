# Alfread Neovim integration

This is a neovim integration for alfread.
It lets you search for folders and will open it with neovim.
TMUX is also integrated, which can be enabled or disabled in the configuration

## Configuration

### Use TMUX

You can decied if you want to use TMUX or not.
If so alfred will create or attach a session called like the folder Path you want to open.
After TMUX is started it will automatically select the pane 0 and starts neovim.

### Name of the Command

You can decided how the command should be.
Default ist `nvim`
