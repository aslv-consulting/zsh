# ZSH

My zsh configuration

## Install

In your .zshrc file, add the following line:

```bash
export zsh_config_path=$HOME/projects/zsh
source ~/projects/zsh/main
```

## Reload configuration

```bash
source ~/.zshrc
```

## Plugins

```bash
# Auto sugestions
git clone https://github.com/zsh-users/zsh-autosuggestions ~/.zsh/zsh-autosuggestions

# Syntax highlighting
git clone https://github.com/zsh-users/zsh-syntax-highlighting ~/.zsh/zsh-syntax-highlighting
```

## App

### Neovim

If you want to use neovim, use the 'v' command.

```bash
brew install neovim
```

### Git

If you want to use git, use the 'g' command.

```bash
# Aliases
git config --global alias.f fetch
git config --global alias.st status
git config --global alias.cm commit
git config --global alias.co checkout
git config --global alias.br branch
git config --global alias.sw switch
git config --global alias.lg "log --oneline --graph --all"
git config --global alias.hist "log --pretty=format:'%h %ad | %s%d [%an]' --graph --date=short"
git config --global alias.tree "log --graph --oneline --decorate --all"
git config --global alias.up "pull --rebase"
git config --global core.editor "nvim"
```
