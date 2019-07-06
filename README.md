# VIM .DOTFILES
Configurations for vim/neovim.

## Requirements Before Installing
- Install python3, including development package.
- Install pynvim with `pip install --user pynvim`.
- Install vimplug with: 
    ```
    curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs
    \ https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
    ```
- Install eslint\_d with `npm install -g eslint\_d`

## Install
1. Clone files into `~/.config/nvim`
2. Open neovim and execute command `:PlugInstall` to install plugins.

