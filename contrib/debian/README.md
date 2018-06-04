
Debian
====================
This directory contains files used to package fssd/fss-qt
for Debian-based Linux systems. If you compile fssd/fss-qt yourself, there are some useful files here.

## fss: URI support ##


fss-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install fss-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your fssqt binary to `/usr/bin`
and the `../../share/pixmaps/fss128.png` to `/usr/share/pixmaps`

fss-qt.protocol (KDE)

