Archiso Live USB with Gnome
===========================

About
-----
This repo is based on the default archiso releng profile, which is used to create the montly installation ISO's. The goal is to create a Live USB disk with a GUI so you can read the wiki while installing Arch Linux on your PC.

The following has been added:
- Gnome
- Gnome Terminal
- Firefox
- nano
- xorg-drivers
- gedit
- eog

Usage
-----
Clone repo and create ISO with mkarchiso:
```
mkarchiso -v -o ./ archiso-liveusb-gnome
```
