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
