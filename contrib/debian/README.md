
Debian
====================
This directory contains files used to package paynayd/paynay-qt
for Debian-based Linux systems. If you compile paynayd/paynay-qt yourself, there are some useful files here.

## paynay: URI support ##


paynay-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install paynay-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your paynayqt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

paynay-qt.protocol (KDE)

