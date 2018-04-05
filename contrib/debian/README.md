
Debian
====================
This directory contains files used to package Onlaxd/Onlax-qt
for Debian-based Linux systems. If you compile Onlaxd/Onlax-qt yourself, there are some useful files here.

## Onlax: URI support ##


Onlax-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install Onlax-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your Onlax-qt binary to `/usr/bin`
and the `../../share/pixmaps/Onlax128.png` to `/usr/share/pixmaps`

Onlax-qt.protocol (KDE)

