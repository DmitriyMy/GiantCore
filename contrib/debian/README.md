
Debian
====================
This directory contains files used to package charedcoind/charedcoin-qt
for Debian-based Linux systems. If you compile charedcoind/charedcoin-qt yourself, there are some useful files here.

## charedcoin: URI support ##


charedcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install charedcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your charedcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/charedcoin128.png` to `/usr/share/pixmaps`

charedcoin-qt.protocol (KDE)

