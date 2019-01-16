
Debian
====================
This directory contains files used to package luckybitd/luckybit-qt
for Debian-based Linux systems. If you compile luckybitd/luckybit-qt yourself, there are some useful files here.

## luckybit: URI support ##


luckybit-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install luckybit-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your luckybit-qt binary to `/usr/bin`
and the `../../share/pixmaps/luckybit128.png` to `/usr/share/pixmaps`

luckybit-qt.protocol (KDE)

