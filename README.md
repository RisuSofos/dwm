# My build of [dwm](https://dwm.suckless.org)

## Installation
for the noobd who need this:
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
