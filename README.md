## My complete setup 
*(this helps me keep track of my workspace and makes it easier to improve carefully)*

Presented as a step by step tutorial to replicate my setup:

## Main computer (macOS)

### Default macOS system settings:
1. Adjust dock
2. Customize Finder
3. Disable Spotlight search

### Essential Tools:
#### Raycast

1. https://www.raycast.com/
2. assign cmd + space to open
 
#### Homebrew

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

#### Alt-Tab

- brew install alttab
#### Hidden bar

- brew install Hidden bar
#### Stats

- brew install Stats
#### Karabiner

- brew install karabiner
- change caps lock to left Ctrl.
#### Aerospace

```zsh
brew install --cask nikitabobko/tap/aerospace
```

After installing, add it to the path. This step shouldn’t be necessary on Intel macs.

Run the following two commands to do so:

```
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"
```

Create configuration file:

```zsh
mkdir -p ~/.config/aerospace
```
```zsh
touch aerospace.toml
```

[aerospace.toml](aerospace.toml)

### Terminal: 
#### Alacritty

1. brew install alacritty
2. Create configuration file:

```zsh
mkdir -p ~/.config/alacritty
```
```zsh
touch alacritty.toml
```
3. [alacritty.toml](alacritty.toml)

#### tmux

1. brew install tmux
2. Create configuration file:

```zsh
mkdir -p ~/.config/tmux
```
```zsh
touch tmux.conf
```
3. [tmux.conf](tmux.conf)
#### oh-my-zsh


#### tree
#### fuzzyfinder
#### zoxide

### Editor

#### Neovim
