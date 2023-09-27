
Debian
====================
This directory contains files used to package bitcoind/a2ncoin-qt
for Debian-based Linux systems. If you compile bitcoind/a2ncoin-qt yourself, there are some useful files here.

## a2ncoin: URI support ##


a2ncoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install a2ncoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your a2ncoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

a2ncoin-qt.protocol (KDE)

