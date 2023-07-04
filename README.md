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

#### macos.lua

This contains MacOS-specific configuration related to clipboard usage, and it is dependent on the operating system being used.

#### maps.lua

This contains all Neovim keymappings that are used in the different keyboard modes.

#### plugins.lua

This contains the Packer definition which packages should be installed and placed under the **plugin** directory.

#### windows.lua

Contains Windows specific configuration regarding clipboard usage and is used dependent on the operating system used.

## Directories

### After

The **after** directory is used to make small changes or configurations to already installed plugins. The following plugins are already configured:

- ./config/nvim/after/plugin/lualine.rc.lua
- ./config/nvim/after/plugin/neosolarized.rc.lua
- ./config/nvim/after/plugin/telescope.rc.lua

### Lua

The **lua** directory contains all files that are used to configure Neovim with Lua commands. The files are loaded within the **init.lua** file in the root directory of the Neovim configuration.

### Plugin

The **plugin** directory normally contains all plugins that are used within Neovim. Because we use Packer to install plugins, all plugins are compiled into one single file and loaded automatically.

## Dependencies

- [homebrew](https://brew.sh/)
- [ripgrep](https://github.com/BurntSushi/ripgrep)

