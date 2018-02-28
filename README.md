[original article link](https://pawelgrzybek.com/sync-vscode-settings-and-snippets-via-dotfiles-on-github/)

### Create simlinks

ln -s /Users/[yourusername]/.dotfiles/VSCode/settings.json /Users/pawelgrzybek/Library/Application\ Support/Code/User/settings.json

ln -s /Users/[yourusername]/.dotfiles/VSCode/keybindings.json /Users/pawelgrzybek/Library/Application\ Support/Code/User/keybindings.json

ln -s /Users/[yourusername]/.dotfiles/VSCode/snippets/ /Users/pawelgrzybek/Library/Application\ Support/Code/User/snippets
