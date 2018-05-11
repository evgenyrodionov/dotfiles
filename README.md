## terminal & git

```sh
# init
cd ~
git clone git@github.com:evgenyrodionov/dotfiles.git

# z & zsh
git clone git@github.com:rupa/z.git
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

# git
ln -sv dotfiles/.gitconfig ~

# iterm & zsh integration
ln -sv dotfiles/.iterm2_shell_integration.zsh ~
defaults write com.googlecode.iterm2.plist PrefsCustomFolder -string "~/dotfiles/iterm"
defaults write com.googlecode.iterm2.plist LoadPrefsFromCustomFolder -bool true

# zsh config
rm ~/.zshrc && ln -sv dotfiles/.zshrc ~
```

## vscode

[Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)
