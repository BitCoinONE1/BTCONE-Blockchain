
Debian
====================
This directory contains files used to package bitcoinoned/bitcoinone-qt
for Debian-based Linux systems. If you compile bitcoinoned/bitcoinone-qt yourself, there are some useful files here.

## bitcoinone: URI support ##


bitcoinone-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitcoinone-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitcoinoneqt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoinone128.png` to `/usr/share/pixmaps`

bitcoinone-qt.protocol (KDE)

