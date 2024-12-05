# My dotfiles

This directory contains the dotfiles for my system

## Requirements

Ensure you have the following installed on your system

```sh
sudo apt install git stow
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```sh
git clone git@github.com:wendingtuo/dotfiles.git
```

then use GNU stow to create symlinks

```sh
stow .
```

## Adding new files

To add new files to the dotfiles directory:
1. `mv` the file from `~/` to `~/dotfiles/` or from `~/.config` to `~/dotfiles/.config`
2. `cd ~/dotfiles`
3. `stow .`
4. `git add .`
5. `git commit -m "commit_message"`
6. `git push`
