
Debian
====================
This directory contains files used to package ddrd/ddr-qt
for Debian-based Linux systems. If you compile ddrd/ddr-qt yourself, there are some useful files here.

## pivx: URI support ##


ddr-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ddr-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ddr-qt binary to `/usr/bin`
and the `../../share/pixmaps/ddr128.png` to `/usr/share/pixmaps`

ddr-qt.protocol (KDE)

