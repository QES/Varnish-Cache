Varnish-Cache
=============

Soft Bans for Varnish Cache 3.0.3

[22nd April 2013 - please note this is a work in progress]

[The code uploaded here is the version I patched and got working on a Amazon Linux AWS install it includes material normally created by autogen.sh which may need to be run on your system

The original patch can be found https://github.com/mbgrydeland/varnish-cache/commit/3c1ccb071df8e9a5ca689e896f6e14098606bc77 and this has been applied to the current varnish 3.0.3 source code http://repo.varnish-cache.org/source/varnish-3.0.3.tar.gz


autogen.sh

./configure

make

make check

make install



see SOFTBANS branch for a version that is patched fromt he base version.

There are two branches in the version.  The MASTER branch contians the code that I have working on Amazon Linux but it includes all the object files.

The SoftBans version is a clean version without the object files BUT I have not yet got it working 100% and it is not the version I am using in production.

