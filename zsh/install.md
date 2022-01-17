

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



### add auto complettion
```bash
brew install zsh-autosuggestions
```

To activate the autosuggestions, add the following at the end of your .zshrc:

    source $(brew --prefix)/share/zsh-autosuggestions/zsh-autosuggestions.zsh