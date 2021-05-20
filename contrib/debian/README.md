
Debian
====================
This directory contains files used to package earnscoind/earnscoin-qt
for Debian-based Linux systems. If you compile earnscoind/earnscoin-qt yourself, there are some useful files here.

## earnscoin: URI support ##


earnscoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install earnscoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your earnscoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/earnscoin128.png` to `/usr/share/pixmaps`

earnscoin-qt.protocol (KDE)

