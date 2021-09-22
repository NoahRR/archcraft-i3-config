- install archcraft
    - NOTE: this will not work on a demo mode (from bootable usb). Need to be running live instal
- run this command:
```
sudo pacman -Syyu && sudo pacman -S archcraft-i3wm
```
- logout, log back in (using i3). Should appear in the WM dropdown in login screen.
- cd ~/.config/
- rename the current i3 directory to i3.old or something
- git clone this repo, then rename the directory to i3
- make sure to install all depencies
