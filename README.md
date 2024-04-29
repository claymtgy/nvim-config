# nvim-config
My personal configuration for Neovim.

This is largely a branch off from [kickstart](https://github.com/nvim-lua/kickstart.nvim)

## Installation:
(When I get one figured out) Execute installation.sh to move the configuration files into .config/nvim
There is an installation.sh file in the repo. It's pretty simple, but I haven't tested it yet. 

This is now a Lua config. Currently using Lazy.nvim
Ensure you have ripgrep installed

The servers that I have installed by default are Volar (for vue.js), tsserver (typescript), phpactor (One for PHP), One for Python.

## PHP LSP
If you wish to use the PHP server, ensure you have Composer installed

### On Debian-based Linux Distros (i.e. Ubuntu):
```sudo apt update && sudo apt install composer```

### On Mac (with Homebrew):
```brew install composer```

## Vue LSP
If you wish to use Volar, ensure you have node installed.

### On Debian-based Linux Distros (i.e. Ubuntu):
``` sudo apt update && sudo apt install node```

### On Mac (with Homebrew):
```brew install node```

## Start:
From there, open Neovim. It should start installing all the plugins. 

Run ```:checkhealth``` to see if everything was installed correctly.

You will probably have to run ```:MasonUpdate``` to update the LSP side of things fully. 

Run :Lazy to check plugins status.

## Keys:
```<leader>``` is configured to " "

```<leader> sf``` will run "find files" using Telescope

```<leader> sg``` will search contents of files

