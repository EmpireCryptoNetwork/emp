
Debian
====================
This directory contains files used to package empirecoind/empirecoin-qt
for Debian-based Linux systems. If you compile empirecoind/empirecoin-qt yourself, there are some useful files here.

## empirecoin: URI support ##


empirecoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install empirecoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your empirecoinqt binary to `/usr/bin`
and the `../../share/pixmaps/empirecoin128.png` to `/usr/share/pixmaps`

empirecoin-qt.protocol (KDE)

