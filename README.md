[original article link](https://pawelgrzybek.com/sync-vscode-settings-and-snippets-via-dotfiles-on-github/)

### Be sure to first shut down VSCode

### Rename the dotfiles directory to .dotfiles after you clone the repo

### Create simlinks

ln -s /Users/[yourusername]/.dotfiles/VSCode/settings.json /Users/[yourusername]/Library/Application\ Support/Code/User/settings.json

ln -s /Users/[yourusername]/.dotfiles/VSCode/keybindings.json /Users/[yourusername]/Library/Application\ Support/Code/User/keybindings.json

ln -s /Users/[yourusername]/.dotfiles/VSCode/snippets/ /Users/[yourusername]/Library/Application\ Support/Code/User/snippets
