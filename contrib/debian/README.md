
Debian
====================
This directory contains files used to package bankittd/bankitt-qt
for Debian-based Linux systems. If you compile bankittd/bankitt-qt yourself, there are some useful files here.

## bankitt: URI support ##


bankitt-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bankitt-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bankitt-qt binary to `/usr/bin`
and the `../../share/pixmaps/bankitt128.png` to `/usr/share/pixmaps`

bankitt-qt.protocol (KDE)

