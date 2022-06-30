# bookmarks.nvim

A Bookmarks Plugin With Global File Store For Neovim Written In Lua.

## Requirements

- Neovim >= 0.7.0

## Installation

[packer.nvim] :

```lua
use {
'tomasky/bookmarks.nvim',
-- tag = 'release' -- To use the latest release
}

```

## Usage

For basic setup with all default configs using [packer.nvim]

```lua
use {
  'tomasky/bookmarks.nvim',
  config = function()
    require('bookmarks').setup()
  end
}
```

Here is an example with most of the default settings:

```lua
require('bookmarks').setup {

}
```

## Credits

- [gitsigns.nvim] most lua functions come from this plugin
- [vim-bookmarks](https://github.com/MattesGroeger/vim-bookmarks) inspired by this vim plugin

[gitsigns.nvim]: https://github.com/lewis6991/gitsigns.nvim
[packer.nvim]: https://github.com/wbthomason/packer.nvim