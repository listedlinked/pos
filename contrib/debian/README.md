
Debian
====================
This directory contains files used to package KALMEXd/KALMEX-qt
for Debian-based Linux systems. If you compile KALMEXd/KALMEX-qt yourself, there are some useful files here.

## KALMEX: URI support ##


KALMEX-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install KALMEX-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your KALMEXqt binary to `/usr/bin`
and the `../../share/pixmaps/KALMEX128.png` to `/usr/share/pixmaps`

KALMEX-qt.protocol (KDE)

