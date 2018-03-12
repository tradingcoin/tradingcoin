
Debian
====================
This directory contains files used to package tradingcoind/tradingcoin-qt
for Debian-based Linux systems. If you compile tradingcoind/tradingcoin-qt yourself, there are some useful files here.

## tradingcoin: URI support ##


tradingcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install tradingcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your tradingcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/tradingcoin128.png` to `/usr/share/pixmaps`

tradingcoin-qt.protocol (KDE)

