# Fterm

A floating terminal window plugin for [NeoVim](https://github.com/neovim/neovim).

# Installation

Install the plugin with your preferred package manager, such as [folke/lazy.nvim](https://github.com/folke/lazy.nvim):

```lua
{
  "profeclipse/fterm.nvim",
  lazy = false,
  config = function()
    -- your personal stuff here
    vim.keymap.set("n", "<leader>tt", "<cmd>Fterm<cr>", desc = { "Toggle floating terminal" })
  end,
}

```

# Usage:

```
:Fterm
```

# Ackowlegement

This initial version is taken entirely from TJ Devries' [advent-of-nvim](https://github.com/tjdevries/advent-of-nvim).
