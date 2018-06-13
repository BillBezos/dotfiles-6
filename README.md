<div align="center">

<img src="screenshot.png" />

[![forthebadge](https://forthebadge.com/images/badges/built-with-science.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/you-didnt-ask-for-this.svg)](https://forthebadge.com)

<p>A set of neovim, zsh, git, and tmux configuration files, made with blood sweat and tears.</p>

</div>

---

## Prerequisites

Make sure the following requirements are installed:

- homebrew
- git
- neovim
- vim-plug
- tmux
- rvm and nvm
- zsh and oh-my-zsh
- universal-ctags
- the_silver_searcher
- reattach-to-user-namespace

## Installation

Clone this project into `~/.dotfiles` directory:

```
$ git clone git@github.com:huyvohcmc/dotfiles.git ~/.dotfiles
```

Create symbolic links:

```
$ cd ~/.dotfiles && ./install.sh
```

## Neovim

You should install [rubocop](https://github.com/bbatsov/rubocop) and [eslint](https://github.com/eslint/eslint) in order for [ALE](https://github.com/w0rp/ale) to work properly:

```
$ gem install rubocop
$ npm install -g eslint
```

## ZSH

Install [purer](https://github.com/DFurnes/purer), a ZSH prompt based on [pure](https://github.com/sindresorhus/pure):

```
$ npm install --global purer-prompt
```

Next, install [zsh-completions](https://github.com/zsh-users/zsh-completions) and [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions). You can visit [awesome-zsh-plugins](https://github.com/unixorn/awesome-zsh-plugins) for more useful stuff.

## Iosevka

I use a custom build of [Iosevka](https://github.com/be5invis/Iosevka) (575 width). Use the default tff from its release if you don't think the font is too narrow.
