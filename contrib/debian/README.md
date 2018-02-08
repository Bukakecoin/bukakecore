
Debian
====================
This directory contains files used to package bukaked/bukake-qt
for Debian-based Linux systems. If you compile bukaked/bukake-qt yourself, there are some useful files here.

## bukake: URI support ##


bukake-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bukake-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bukake-qt binary to `/usr/bin`
and the `../../share/pixmaps/bukake128.png` to `/usr/share/pixmaps`

bukake-qt.protocol (KDE)

