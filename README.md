# j_blow_emacs_theme_nvim
Jonathan Blows Theme for NVIM

# Install
```
cp ~/Downloads/naysayer.vim ~/.config/nvim/colors/
```

# Set Color and colorscheme in init.lua
```
vim.o.termguicolors = true
vim.cmd('colorscheme naysayer')
```

# Remove the signcolumn
```
vim.wo.signcolumn = 'no'
```

#Lua Line Theming to Seoul256
```
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
