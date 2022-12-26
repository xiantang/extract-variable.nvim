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
