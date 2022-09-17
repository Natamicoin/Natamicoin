
Debian
====================
This directory contains files used to package natamid/natami-qt
for Debian-based Linux systems. If you compile natamid/natami-qt yourself, there are some useful files here.

## natami: URI support ##


natami-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install natami-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your natami-qt binary to `/usr/bin`
and the `../../share/pixmaps/natami128.png` to `/usr/share/pixmaps`

natami-qt.protocol (KDE)

