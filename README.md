Varnish-Cache
=============

Soft Bans for Varnish Cache 3.0.3

[22nd April 2013 - please note this is a work in progress]

[The code uploaded here is the version I patched and got working on a Amazon Linux AWS install it includes material normally created by autogen.sh AND the object files created from running make.  These may need to be cleaned up by runing autogen.sh and configure on your system followed by a make clean ]

The original patch can be found https://github.com/mbgrydeland/varnish-cache/commit/3c1ccb071df8e9a5ca689e896f6e14098606bc77 and this has been applied to the current varnish 3.0.3 source code http://repo.varnish-cache.org/source/varnish-3.0.3.tar.gz


autogen.sh

./configure

make clean

make

// make check    [if you want to check the install - if you just want to check SoftBans then

//                runs ./varnishtest -i -j3 ./tests/*.vtc

//

//          cd bin/varnishtest

//          sh ./varnishtest -i -j3 ./tests/s0000*.vtc

//          # this checks that the softbans code is working by running those tests.


make install

       =======================

The MASTER branch contians the code that I have working on Amazon Linux but it includes all the object files.

There is a second version of this on Github that I am working on that is patched into the origianl soruce but that version which is a clean version without the object files etc BUT I have not yet got it working 100% and it is not the version I am using in production.



