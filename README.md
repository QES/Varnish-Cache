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
