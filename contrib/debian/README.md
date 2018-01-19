
Debian
====================
This directory contains files used to package sgprd/sgpr-qt
for Debian-based Linux systems. If you compile sgprd/sgpr-qt yourself, there are some useful files here.

## sgpr: URI support ##


sgpr-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install sgpr-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your sgpr-qt binary to `/usr/bin`
and the `../../share/pixmaps/sgpr128.png` to `/usr/share/pixmaps`

sgpr-qt.protocol (KDE)

