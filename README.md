# wake

Small Python script to invoke wakeonlan.

## Requirements

You have to install wakeonlan (and Python):

### in Debian

sudo apt-get install wakeonlan

### in Arch

This AUR package: https://aur.archlinux.org/packages/wakeonlan/

```
git clone https://aur.archlinux.org/wakeonlan.git
cd wakeonlan
makepkg -csi
```

## Install

Just copy it to your bin directory (i.e. ~/bin) and edit wake.macs (the list of hostname - MAC address pairs that you want to use). I use 'wk' as a symbolic link:

```
ln -s ~/bin/wake ~/bin/wk
```
