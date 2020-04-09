## Installation

### macOS

```bash
    brew install tmux zsh
    
    # chsh -s $(which zsh)

    # brew install reattach-to-user-namespace
    brew tap homebrew/cask-fonts
    brew cask install font-fira-code # font-jetbrains-mono
    # brew install byobu
```

### Linux

```bash
    sudo add-apt-repository universe
    sudo apt-get update
    sudo apt-get install tmux zsh vim fonts-firacode
    # sudo apt-get install byobu

    # chsh -s $(which zsh)

    # wget https://download.jetbrains.com/fonts/JetBrainsMono-1.0.0.zip
    # unzip JetBrainsMono-1.0.0.zip
    # sudo mv JetBrainsMono-*.ttf /usr/share/fonts/
    # :set guifont=JetBrains\ Mono\ 13
```

```bash
➜ git clone https://github.com/adamhudsonnall/dotfiles.git
➜ ./install.sh
```

## Thanks to…

* [Mathias Bynens](https://github.com/mathiasbynens/dotfiles)
* [Gregory Pakosz](https://github.com/gpakosz/.tmux)
* [Nick Nisi](https://github.com/nicknisi/dotfiles)
* [Fira Code](https://github.com/tonsky/FiraCode)