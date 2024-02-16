# my-dotfiles

This repository is where I store my personal configuration for [Neovim], [tmux], etc. Feel free to replicate my settings.

## Neovim
I use [LazyVim] with some minor changes. Most of the settings I use are already provided by LazyVim out of the box. The changes include:
- [Catppuccin] as the default colorscheme;
- [vim-tmux-navigator] for smoother navigation with tmux;
- Extra remaps.

[LazyVim]: https://github.com/LazyVim/LazyVim
[Catppuccin]: https://github.com/catppuccin/nvim
[vim-tmux-navigator]: https://github.com/christoomey/vim-tmux-navigator

## tmux
My tmux configuration includes:
- `history-limit` set to `10000`;
- `C-Space` as the new prefix;
- Plugins like [vim-tmux-navigator] and [Catppuccin (tmux)] for theming.

[vim-tmux-navigator]: https://github.com/christoomey/vim-tmux-navigator
[Catppuccin (tmux)]: https://github.com/catppuccin/tmux
