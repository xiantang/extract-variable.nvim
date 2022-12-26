# extract-value.nvim

A Neovim plugin for extracting values function parameters, this plugin depends on [nvim-treesitter-textobjects](https://github.com/nvim-treesitter/nvim-treesitter-textobjects)

## Showcase

![extract-value](https://user-images.githubusercontent.com/34479567/209532406-29b3cf56-5f33-4664-80e2-79e51b05db07.gif)

## Installation


```lua
use({
	"xiantang/extract-value.nvim",
	config = function()
		require("extract_value").setup()
	end,
	require = { "nvim-treesitter/nvim-treesitter-textobjects" },
})
```


