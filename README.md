# David Dotflies
---
## New Mac Install
1. Command Line Tools for Git and Brew
```xcode-select --install```
2. Clone repo into a new hidden directory
```git clone git@github.com:DLevai94/dotfiles.git```
3. Symlinks!
```
ln -s ~/.dotfiles/.zshrc ~/.zshrc
ln -s ~/.dotfiles/.gitconfig ~/.gitconfig
```
4. Install Homebrew and softwares
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

brew bundle --file ~/.dotfiles/Brewfile
```