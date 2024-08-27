# My dotfiles

This directory contains the dotfiles for my system

## Requirements

Ensure you have the following installed on your system

```
sudo apt install git stow
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```
$ git clone git@github.com/wendingtuo/dotfiles.git
$ cd dotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```

## Adding new files

To add new files to the dotfiles directory:
1. `mv` the file from ~/ or ~/.config to ~/dotfiles/ or ~/dotfiles/.config (respectively)
2. `cd ~/dotfiles`
3. `stow .`
4. `git add .`
5. `git commit -m "commit_message"`
6. `git push`
