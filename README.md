## Homebrew

It's dangerous to go alone! Take this.

``` bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Terminal Setup

Adapted from [josean](https://www.josean.com/posts/terminal-setup)

### Nord Theme

An arctic, north-bluish clean and elegant Terminal.app color theme.

[nordtheme / terminal-app](https://github.com/nordtheme/terminal-app)

### Oh My ZSH

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### Powerlevel10k

``` bash
git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
```

Modify the `~/.zshrc` file to set the theme.
```
ZSH_THEME="powerlevel10k/powerlevel10k"
```

### Oh My ZSH Plugins
#### zsh-autosuggestions
```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

#### zsh-syntax-highlighting
```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

#### update ~/.zshrc
```
plugins=(
    git 
    zsh-autosuggestions 
    zsh-syntax-highlighting
)
```

### Install MesloNerd font.

[ryanoasis / nerd-fonts](https://github.com/ryanoasis/nerd-fonts/releases)


## Text Editor

### VSCodium

```
brew install --cask vscodium
```

### One Dark Pro

Atom's iconic One Dark theme for Visual Studio Code

[VS Marketplace Link](https://open-vsx.org/vscode/item?itemName=zhuangtongfa.material-theme)

