# Neovim Config

Configuration is based on the following YouTube Videos:

- [How to set up Neovim for coding React, TypeScript, Tailwind CSS, etc on a new M2 MacBook Air](https://youtu.be/ajmK0ZNcM4Q)

## Files

### init.lua

This section contains the definitions of files that are loaded when Neovim starts.

#### base.lua

This contains all basic configuration like visual options etc..

#### highlights.lua

This contains the syntax highlighting configuration that is used in Neovim.

#### maps.lua

This contains all Neovim keymappings that are used in the different keyboard modes.

#### plugins.lua

This contains the Lazy definition which packages should be installed.

## Directories

### After

The **after** directory is used to make small changes or configurations to already installed plugins. The following plugins are already configured:

- ./config/nvim/after/plugin/lualine.rc.lua
- ./config/nvim/after/plugin/solarized-osaka.rc.lua

### Lua

The **lua** directory contains all files that are used to configure Neovim with Lua commands. The files are loaded within the **init.lua** file in the root directory of the Neovim configuration.

## Dependencies

- [homebrew](https://brew.sh/)
- [ripgrep](https://github.com/BurntSushi/ripgrep)
- [fd](https://github.com/sharkdp/fd)

