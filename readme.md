# nvim-config

## install neovim

```shell
sudo apt install neovim
```

```shell
sudo pacman -S neovim
```

## check neovim version

```shell
nvim --version
```

## create neovim link

```shell
sudo ln -s /usr/bin/nvim /usr/bin/neovim
```

## clone this repository

```shell
cd ~/.config
```

```shell
git clone git@github.com:managanemeke/nvim-config.git nvim
```

```shell
cd nvim
```

## install packer and plugins

```shell
git clone --depth 1 https://github.com/wbthomason/packer.nvim \
  ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```

```shell
nvim lua/plugins.lua
```

```vim
:PackerSync
```

## links

- [one-nvim-to-rule-them-all](https://habr.com/ru/articles/706110/)
