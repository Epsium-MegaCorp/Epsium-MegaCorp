
Debian
====================
This directory contains files used to package epsiumd/epsium-qt
for Debian-based Linux systems. If you compile epsiumd/epsium-qt yourself, there are some useful files here.

## pivx: URI support ##


epsium-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install epsium-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your epsium-qt binary to `/usr/bin`
and the `../../share/pixmaps/epsium128.png` to `/usr/share/pixmaps`

epsium-qt.protocol (KDE)

