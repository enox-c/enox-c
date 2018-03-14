
Debian
====================
This directory contains files used to package enoxd/enox-qt
for Debian-based Linux systems. If you compile enoxd/enox-qt yourself, there are some useful files here.

## enox: URI support ##


enox-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install enox-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your enoxqt binary to `/usr/bin`
and the `../../share/pixmaps/enox128.png` to `/usr/share/pixmaps`

enox-qt.protocol (KDE)

