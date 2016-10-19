# Terminal

### Install zsh

* 使用Homebrew安裝zsh:

```
brew install zsh
```

* 預設shell調整為zsh:

link = /usr/local/bin/zsh || /bin/zsh

```
chsh -s {link}
```

或

單獨調整terminal的預設shell:

Preferences > Genrals > Shells open with {link}


### Install oh-my-zsh

```
git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh
cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
```

### Install zsh-syntax-highlighting

```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ~/.zsh-syntax-highlighting
echo "source ${(q-)PWD}/.zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc
```

### Download Iterm2-color-schemes

http://iterm2colorschemes.com/
