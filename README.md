# reverse.nvim

- `reverse.nvim` is a simple Neovim plugin that allows you to reverse the lines in your buffer. You can reverse the entire buffer in normal mode or reverse a selected range of lines in visual mode.
- Yeah! I know its a useless plugin, but I needed it just for one time, so here it is, for future needs.

## Installation
### Using [lazy.nvim](https://github.com/folke/lazy.nvim)

```lua
{
    "svban/reverse.nvim",
    cmd = { "Reverse" },
    opts = {},
}
```

## Usage
- in Normal or Visual mode `:Reverse`

## Inspiration
- [reverse.vim](https://github.com/vim-scripts/reverse.vim)
