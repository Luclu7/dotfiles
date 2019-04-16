# Dotfiles
<h1 align="center"><br>
<img src="https://raw.githubusercontent.com/luclu7/dotfiles/master/dotfiles.png" alt="random dotfiles icon" width="300em">
<br><br>
</h1>

Those are ~all my dotfiles, install them if you want via GNU Stow:
```
git clone https://github.com/luclu7/dotfiles ~/dotfiles
cd ~/dotfiles
stow -v vim
stow -v i3
stow -v termite
stow -v bins
stow -v fish
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
vim :PluginInstall
```

Dependencies:
* j4-dmenu-desktop
* rofi
* termite
* udiskie
* [xcwd](https://github.com/schischi/xcwd)
* gnome-screenshot
* pa-applet
* xbacklight
* mpd/mpc
* python
* redshift
* gnome-keyring
* vim


Screenshot:
![screenshot](screenshot.png)
