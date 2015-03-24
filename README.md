a20-olinuxino-micro-autobuild
=============================

This is automatic build system for A20 OLinuXino Micro.


# To setup your host environment you should do something like this on Ubuntu 14.04:
sudo apt-get install git build-essential gperf bison flex texinfo gawk libtool automake libncurses5-dev subversion mercurial

# And probably with the wrong make, one should installing this version of make for building buildroot:
wget ftp://gnu.mirror.iweb.com/make/make-3.82.tar.gz
tar -xf make-3.82.tar.gz 
cd make-3.82/
./configure
make
sudo make install


With thanks to mireq for the original code.

More information on [wiki](https://github.com/mireq/a20-olinuxino-micro-autobuild/wiki)
