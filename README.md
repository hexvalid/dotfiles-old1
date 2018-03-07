# dotfiles

## installation

```

# fonts
sudo mkdir -p /usr/share/fonts/OTF
sudo cp fonts/* /usr/share/fonts/OTF/

# configs
mkdir -p $HOME/.config/i3
cp -r .config/* $HOME/.config/
cp .Xresources $HOME/

# install vim plugins
vim +PluginInstall +qall


```

**used packages**

```
i3-gaps-git i3blocks-gaps-git
vim vundle-git


```
