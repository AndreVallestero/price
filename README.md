# price
An auto ricing script with a focus on P as in Performance, Productivity, and Practicality

Heavily inspired and derived from [LARBS](https://github.com/LukeSmithxyz/LARBS)

## Features
* Create a new user or use an existing one
* Option to setup hostname and host IPs
* Option to setup auto-login after boot
* Option to setup auto-startx after login
* Option to generate a sorted mirrorlist
* Option to remove source packages from /usr/local/src after installing
* Option to use /etc/ configuration files

## Packages
### pacman packages:
* base
* base-devel
* git
* NetworkManager
* ttf-roboto
* stow
* reflector
* pigz
* qt5ct
* qtconfig-qt4
* dunst
* mutt
* neovim
* light
* pulseaudio
* pulsemixer
* nnn
* zathura
* ncmpcpp
* transmission
* calcurse

### aur packages:
* yay
* ttf-roboto-slab
* ttf-roboto-mono
* ttf-emojione
* slock-gruvbox (optional)

### source packages:
* https://github.com/AndreVallestero/dmenu.git
* https://github.com/AndreVallestero/st.git
    * scrollback (apply conflicts with mouse scroll)
    * anysize
* https://github.com/AndreVallestero/dwm.git
    * systray (apply conflicts)
* https://github.com/AndreVallestero/dwm-status.git
* https://github.com/LukeSmithxyz/mutt-wizard.git

### dotfiles:
* https://github.com/AndreVallestero/dotfiles.git
