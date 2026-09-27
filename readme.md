# nvim-config

## install neovim

```bash
sudo apt install neovim
```

```bash
sudo pacman -S neovim
```

## check neovim version

```bash
nvim --version
```

## create neovim link

```bash
sudo ln -s /usr/bin/nvim /usr/bin/neovim
```

## clone this repository

```bash
cd ~/.config
```

```bash
git clone git@github.com:managanemeke/nvim-config.git nvim
```

```bash
cd nvim
```

## install packer and plugins

```bash
git clone --depth 1 https://github.com/wbthomason/packer.nvim \
  ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```

```bash
nvim lua/plugins.lua
```

```vim
:PackerSync
```

## install lsp

```vim
:Mason
```

- lua-language-server (lua)
- pyright (python)

## links

- [one-nvim-to-rule-them-all](https://habr.com/ru/articles/706110/)
- [fastest-vimer](https://youtu.be/y6VJBeZEDZU?si=_-0nfEhPhGH4DaEQ)
