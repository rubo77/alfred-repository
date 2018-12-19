alfred-repository
=================

installed from http://debian.draic.info/pool/main/a/alfred/

	mkdir /tmp/alfred-tempbuild
	cd /tmp/alfred-tempbuild
	wget http://debian.draic.info/pool/main/a/alfred/alfred_2014.3.0.orig.tar.gz
	unp alfred_2014.3.0.orig.tar.gz
	cd alfred-2014.3.0/
	wget http://debian.draic.info/pool/main/a/alfred/alfred_2014.3.0-11.debian.tar.gz
	unp alfred_2014.3.0-11.debian.tar.gz
	mv alfred_2014.3.0-11.debian.tar.gz ../
	dpkg-buildpackage -b -us -uc

Install
===

	cd /tmp/
	wget https://github.com/ffnord/alfred-repository/blob/master/alfred_2014.3.0-11_i386.deb?raw=true
	sudo dpkg -i alfred_2014.3.0-11_i386.deb
	wget https://github.com/ffnord/alfred-repository/blob/master/batadv-vis_2014.3.0-11_i386.deb?raw=true
	sudo dpkg -i batadv-vis_2014.3.0-11_i386.deb 
