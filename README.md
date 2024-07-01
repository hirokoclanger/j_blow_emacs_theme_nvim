
Jonathan Blows Theme for NVIM
![Neovim Theme](https://github.com/hirokoclanger/j_blow_emacs_theme_nvim/blob/4d07c76201ed425f8bedd8a137337c876ea75d8c/j_blow_theme_nvim)
### Install
```lua
cp ~/Downloads/naysayer.vim ~/.config/nvim/colors/
```

### Set colormode, cursor color and colorscheme in init.lua
```lua
vim.o.termguicolors = true
vim.cmd('colorscheme jblow')
vim.opt.guicursor = "n-v-c:block-Cursor/lCursor"
```

### Remove the signcolumn
```lua
vim.wo.signcolumn = 'no'
```

### Lua Line Theming to Seoul256
```lua
 {
    -- Set lualine as statusline
    'nvim-lualine/lualine.nvim',
    -- See `:help lualine.txt`
    opts = {
      options = {
        icons_enabled = false,
        theme = 'seoul256',
        component_separators = '|',
        section_separators = '',
      },
    },
  },
```
