# My build of [dwm](https://dwm.suckless.org)

## Requirements
xorg-server xorg-xinit libx11 libxinerama libxft webkit2gtk

## Installation
for the noobs who need this:
```sh
git clone https://github.com/RisuSofos/dwm
cd dwm
sudo make clean install
```

append the following to `.xinitrc` and disable other window managers/desktops
```bash
nitrogen --restore &
xcompmgr &
exec dwm
```

add `startx` to `.bash_profile`

## KeyBinds
###Coming Soon
