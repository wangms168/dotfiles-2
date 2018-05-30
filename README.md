![](./screenshot.png)
### Dotfiles
---
This repository hosts the dotfiles i use in my daily life. They should be cloned to your home directory, the path is `~/dotfiles/`.The script `install.sh` does two things:  
1. backup your config files(if exist) to `~/dotfiles_old`.
2. copy my config files for `awesomewm` & `tmux` & `vim` & `urxvt` & `zsh` to you.
### Before installation
---
- Before installation, `awesomewm` & `tmux` & `vim` & `urxvt` & `zsh` are supposed to be installed.
- Because i use **vundle** as the Vim plugin manager, you also need to install [Vundle](https://github.com/VundleVim/Vundle.vim).And vundle is an awesome plugin manager for Vim.(the `install.sh` will help you do this if you did't)
- Set the default shell to **zsh** if it is not the current shell.You also need to install [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) for your zsh's configuration.(the `install.sh` will help you do this if you did't)
- The pkglist in the file is for backup my installed packages, you can ignore it.
### Installation
---
```bash
git clone https://github.com/Trytwice/dotfiles.git ~/dotfiles && cd ~/dotfiles && ./install.sh
```
### Customization
- **WallPaper**:The system's wallpaper is `~/.config/awesome/themes/powerarrow-dark/wall.png`, delete it and move you new wallpaper here and rename it as `wall.png`.
- **The music widget**:To use the music widget, you need install **mpd** and **mpc**.Search [ArchWiKi](https://wiki.archlinux.org/index.php/Music_Player_Daemon) for more details.
- **About NERDTree and ctrlp**:i map **<F2>** for NERDTreeToggle and **<F3>** for ctrlp, you can remap it whatever you want in `~/.vimrc` in the end of the file.

