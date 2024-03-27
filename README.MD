# Nvim as Python / C/C++ / any another language IDE!

Install [neovim](https://github.com/neovim/neovim/blob/master/INSTALL.md)

Install also [vim-plug](https://github.com/junegunn/vim-plug) — plugin manager for vim/nvim.

Put [init.vim](init.vim) to `~/.config/nvim/init.vim` folder.

## Language support
Find and install lsp for your language. Then add its name to the `servers` list. Example:
```
local servers = { 'pyright', 'rust_analyzer' }
```

Install [ripgerp](https://github.com/BurntSushi/ripgrep?tab=readme-ov-file#installation)
## LSP
For C/C++ -- [clangd](https://clangd.llvm.org/installation)
For python -- [pyright](https://github.com/microsoft/pyright)
