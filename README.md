# zsh-macos
zsh configuration adapted for macos based on [Kali Linux](https://kali.org) [2020.3 release](https://www.kali.org/news/kali-2020-3-release/)

![zsh](https://statropy.com/img/banners/zsh-macos.png)

This .zshrc file uses a similar config as Kali Linux, but also includes git status with the prompt.

## Install

Install the [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting), [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) and [menlo powerline font](https://github.com/powerline/fonts) packages using [Homebrew](https://brew.sh/).

```
brew install zsh-syntax-highlighting zsh-autosuggestions homebrew/cask-fonts/font-menlo-for-powerline
```

Backup the existing `.zshrc` and symlink the .zshrc file from this repo to your home directory.

```
git clone https://github.com/statropy/zsh-macos.git
mv ~/.zshrc ~/.zshrc.orig
ln -s ./zsh-macos/.zshrc ~/.zshrc
```

In the Terminal Preferences for the selected Profile, change the font to `Menlo for Powerline`. Quit and restart Terminal.

To add your own alias or other commands without having to edit `.zshrc`, create a `.alias` file in the home directory. The `.zshrc` file will load it if it exists.
