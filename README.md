# init.lua

Personal nvim config. Thanks for checking it out.

# Prerequisites

nvim >= 0.9.2

# Install

## 0. Delete existing config (optional)
Run `rm -rf ~/.local/share/nvim/site/pack/packer` and `rm -rf ~/.config/nvim`.

## 1. [Install packer](https://github.com/wbthomason/packer.nvim#quickstart) (may be subject to change, check the link):
### Linux:
`git clone --depth 1 https://github.com/wbthomason/packer.nvim ~/.local/share/nvim/site/pack/packer/start/packer.nvim`
### Windows:
`git clone https://github.com/wbthomason/packer.nvim "$env:LOCALAPPDATA\nvim-data\site\pack\packer\start\packer.nvim"`

## 2. Install the config
### Linux:
`git clone https://github.com/ikalinic/init.lua ~/.config/nvim`
### Windows:
`git clone https://github.com/ikalinic/init.lua "$env:LOCALAPPDATA\nvim"`

## 3. Register the config in neovim
  Inside nvim, go to `~/.config/nvim/lua/ikkjo` and `:so` all of the files.
