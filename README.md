# dotfiles

Save all my configuration files

# Setup steps

## Install Homebrew

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/gioraguttsait/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"
```

## Install OhMyZsh

```sh
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

Now copy `.zsh_aliases.sh  .zshrc` to your `~`

## Install stuff with Homebrew

```sh
brew install git
mkdir ~/.nvm && brew install nvm
```
