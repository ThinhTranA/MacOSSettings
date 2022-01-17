

### oh my zsh install
```bash
$ sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### syntax highlighting
```bash
brew install zsh-syntax-highlighting
```
To activate the syntax highlighting, add the following at the end of your .zshrc:
    source $(brew --prefix)/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh



### add auto suggestions
```bash
brew install zsh-autosuggestions
```

To activate the autosuggestions, add the following at the end of your .zshrc:

    source $(brew --prefix)/share/zsh-autosuggestions/zsh-autosuggestions.zsh

### add vi mode (vim)
```bash
brew install zsh-vi-mode
```

To activate the zsh vi mode, add the following line to your .zshrc:
    source $(brew --prefix)/opt/zsh-vi-mode/share/zsh-vi-mode/zsh-vi-mode.plugin.zsh
