
Debian
====================
This directory contains files used to package worldpaycoind/worldpaycoin-qt
for Debian-based Linux systems. If you compile worldpaycoind/worldpaycoin-qt yourself, there are some useful files here.

## worldpaycoin: URI support ##


worldpaycoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install worldpaycoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your worldpaycoinqt binary to `/usr/bin`
and the `../../share/pixmaps/worldpaycoin128.png` to `/usr/share/pixmaps`

worldpaycoin-qt.protocol (KDE)

