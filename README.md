## terminal & git

```sh
# z & zsh
git clone git@github.com:rupa/z.git
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

# git
ln -sv dotfiles/.gitconfig ~

# iterm & zsh integration
ln -sv dotfiles/.iterm2 ~
ln -sv dotfiles/.iterm2_shell_integration.zsh ~

# zsh config
rm ~/.zshrc && ln -sv dotfiles/.zshrc ~
```

## vscode

[Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)
