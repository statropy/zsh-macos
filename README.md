# zsh-macos
zsh configuration adapted for macos based on [Kali Linux](https://kali.org) [2020.3 release](https://www.kali.org/news/kali-2020-3-release/)

![Kali Linux zsh](https://www.kali.org/wp-content/uploads/2020/08/release-2020.3-zsh.png)

## Install

Copy the .zshrc file in this repo to your home directory (after backing up the original if it exists)

```
mv ~/.zshrc ~/.zshrc.orig
cp .zshrc ~/.zshrc
```

Install the [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) and [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) packages using [Homebrew](https://brew.sh/)

```
brew install zsh-syntax-highlighting zsh-autosuggestions
```

If already using zsh, load the update .zshrc file

```
source ~/.zshrc
```

or if using another shell, start zsh

```
zsh
```
