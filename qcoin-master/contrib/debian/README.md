
Debian
====================
This directory contains files used to package qcoind/qcoin-qt
for Debian-based Linux systems. If you compile qcoind/qcoin-qt yourself, there are some useful files here.

## qcoin: URI support ##


qcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install qcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your qcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/qcoin128.png` to `/usr/share/pixmaps`

qcoin-qt.protocol (KDE)

