# How to use

To install this for your neovim configuration

```
git clone -b v2.0 https://github.com/NvChad/NvChad ~/.config/nvim --depth 1
git clone https://github.com/polemeest/neovim-python.git ~/.config/nvim/lua/custom
```

Then open up neovim and let everything install. If not installed automatically, then enter this in command line:

```
MasonInstallAll
```

Restart Neovim and install the treesitter syntax

```
:TSInstall python
```
