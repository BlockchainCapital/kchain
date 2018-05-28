
Debian
====================
This directory contains files used to package kchaind/kchain-qt
for Debian-based Linux systems. If you compile kchaind/kchain-qt yourself, there are some useful files here.

## kchain: URI support ##


kchain-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install kchain-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your kchain-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

kchain-qt.protocol (KDE)

