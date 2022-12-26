# extract-value.nvim

A Neovim plugin for extracting values function parameters, this plugin depends on [nvim-treesitter-textobjects](https://github.com/nvim-treesitter/nvim-treesitter-textobjects)


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

## Showcase

![extract-value](https://user-images.githubusercontent.com/34479567/209531891-5bf4038e-6d58-45e5-8e79-f27628f35beb.gif)
