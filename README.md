Tvheadend
====================================
(c) 2006 - 2014 Tvheadend Foundation CIC


What it is
----------

Tvheadend is a TV streaming server and digital video recorder.

It supports the following inputs:

  * DVB-C
  * DVB-T(2)
  * DVB-S(2)
  * ATSC
  * IPTV
    * UDP
    * HTTP

How to build for Linux
----------------------

First you need to configure:

	$ ./configure

If any dependencies are missing the configure script will complain or attempt
to disable optional features.

Build the binary:

	$ make

After build, the binary resides in `build.linux` directory.

Thus, to start it, just type:

	$ ./build.linux/tvheadend

Settings are stored in `$HOME/.hts/tvheadend`.


Further information
-------------------

For more information about building, including generating packages, please visit:
> https://tvheadend.org/projects/tvheadend/wiki/Building  
> https://tvheadend.org/projects/tvheadend/wiki/Packaging  
> https://tvheadend.org/projects/tvheadend/wiki/Git
