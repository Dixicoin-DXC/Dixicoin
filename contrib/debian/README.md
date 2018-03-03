
Debian
====================
This directory contains files used to package dixicoind/dixicoin-qt
for Debian-based Linux systems. If you compile dixicoind/dixicoin-qt yourself, there are some useful files here.

## dixicoin: URI support ##


dixicoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dixicoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dixicoinqt binary to `/usr/bin`
and the `../../share/pixmaps/dixicoin128.png` to `/usr/share/pixmaps`

dixicoin-qt.protocol (KDE)

