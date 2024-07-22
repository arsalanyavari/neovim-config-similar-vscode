This is a repository contains lua config for neovim that make vim similar to VSCode.

You can use `Ctrl+b` for **file tree**, `Ctrl+j` for **Terminal** and `Ctrl+s` for **Saving contents**.
If there is a problem and it is not in [issues list](https://github.com/arsalanyavari/neovim-config-similar-vscode/issues), [create an issue](https://github.com/arsalanyavari/neovim-config-similar-vscode/issues/new/choose).

demo:

<img width="100%" src="https://github.com/arsalanyavari/neovim-config-similar-vscode/blob/main/demo.gif">

Quick setup:
```bash
if [ -f "$HOME/.config/nvim/init.lua" ]; then mv "$HOME/.config/nvim/init.lua" "$HOME/.config/nvim/init.lua.old"; fi
cd /tmp && git clone https://github.com/arsalanyavari/neovim-config-similar-vscode \
&& mv neovim-config-similar-vscode/init.lua $HOME/.config/nvim/init.lua && nvim '+PackerInstall'
``` 
