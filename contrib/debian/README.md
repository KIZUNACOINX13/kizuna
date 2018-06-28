
Debian
====================
This directory contains files used to package kizd/kiz-qt
for Debian-based Linux systems. If you compile kizd/kiz-qt yourself, there are some useful files here.

## kiz: URI support ##


kiz-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install kiz-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your kizqt binary to `/usr/bin`
and the `../../share/pixmaps/kiz128.png` to `/usr/share/pixmaps`

kiz-qt.protocol (KDE)

