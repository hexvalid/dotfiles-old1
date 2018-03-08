# dotfiles

## installation

```
# xorg
sudo cp etc/X11/xorg.conf /etc/X11/xorg.conf

# fonts
sudo mkdir -p /usr/share/fonts/OTF
sudo cp fonts/* /usr/share/fonts/OTF/

# configs
mkdir -p $HOME/.config/i3
cp -r .config/* $HOME/.config/
cp .Xresources $HOME/
cp .xinitrc $HOME/

# install vim plugins
vim +PluginInstall +qall
```

**used packages**

```
nvidia xorg-xrandr xorg-xgamma xorg-xinit
feh
i3-gaps-git i3blocks-gaps-git
vim vundle-git
```
