
Debian
====================
This directory contains files used to package edelweisd/edelweis-qt
for Debian-based Linux systems. If you compile edelweisd/edelweis-qt yourself, there are some useful files here.

## pivx: URI support ##


edelweis-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install edelweis-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your edelweis-qt binary to `/usr/bin`
and the `../../share/pixmaps/edelweis128.png` to `/usr/share/pixmaps`

edelweis-qt.protocol (KDE)

