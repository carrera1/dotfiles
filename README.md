# My dotfiles

Just the dot files I drag around for bash, vim, and tmux

## bash

"Inspired" by parrotOS' default bash environment. I tend to keep .bashrc super minimal, and just ```source ~/.bash_profile``` from it. This initially started out bc macOS by default saved bash configuration things in this dot file. 

## tmux

Mainly, C-a replaces C-b for session controls because it just... *feels better*. I also type on a HHKB where CAPS LOCK is replaced by CTRL, so C-a ends up being as easy as breathing. Note that from the command line this unfortunately means that the usual C-a command line shortcut will be 'C-a a' while using tmux... annoying now that I think of it.

Window splitting is slightly changed to be more logical to my brain. 'C-a s' accomplishes a horizontal spit, whereas 'C-a v' will do a vertical. 

Swapping windows uses vim-like controls: C-h, C-j, C-k, C-l for left, down, up, and right respectively. Note that from the command line this unfortunately kills the C-k line kill shortcut... might change this in the future or just... learn to use screen instead of tmux.

## vim

Will require vundle to actually use the plugins. Totally worth it though.

If using neovim, no big deal. See ':help nvim-from-vim'
