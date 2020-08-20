# zsh-macos
zsh configuration adapted for macos based on [Kali Linux](https://kali.org) [2020.3 release](https://www.kali.org/news/kali-2020-3-release/)

![Kali Linux zsh](https://www.kali.org/wp-content/uploads/2020/08/release-2020.3-zsh.png)


This .zshrc file uses the same config as Kali Linux, but also includes git status with the prompt.

## Install

Install the [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting), [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) and [menlo powerline font](https://github.com/powerline/fonts) packages using [Homebrew](https://brew.sh/).

```
brew install zsh-syntax-highlighting zsh-autosuggestions homebrew/cask-fonts/font-menlo-for-powerline
```

Backup the existing .zshrc and copy the .zshrc file from this repo to your home directory.

```
mv ~/.zshrc ~/.zshrc.orig
cp .zshrc ~/.zshrc
```

In the Terminal Preferences for the selected Profile, change the font to `Menlo for Powerline`.

If already using zsh, load the updated .zshrc file.

```
source ~/.zshrc
```

or if using another shell, start zsh

```
zsh
```

If you want to make zsh your default shell:

```
chsh -s /bin/zsh
```
