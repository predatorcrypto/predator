
Debian
====================
This directory contains files used to package predatorcoind/predatorcoin-qt
for Debian-based Linux systems. If you compile predatorcoind/predatorcoin-qt yourself, there are some useful files here.

## predatorcoin: URI support ##


predatorcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install predatorcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your predatorcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/predatorcoin128.png` to `/usr/share/pixmaps`

predatorcoin-qt.protocol (KDE)

