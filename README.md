# ghosttybuddy.nvim - a neovim theme for ghostty terminal users

## Installation

### lazy
```lua
return {
	"hgranthorner/ghosttybuddy.nvim",
	dependencies = {
		"tjdevries/colorbuddy.nvim"
	},
	lazy = false,
	priority = 1000,
	config = function()
		vim.cmd.colorscheme 'ghostty'
	end
}
```

