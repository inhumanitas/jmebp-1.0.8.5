=============
Fork jmebp-1.0.8.5
=============

fork of jmebp v1.0.8.5

This is the ethernet driver is for JMicron chip.
Forked only to hard fix compile problem under Fedora 19.

To see the current driver version run in terminal 
  ethtool -i *interface*
Example:
  $ethtool -i p5p1
  
To compile you need kernel-headers and compiler!

Simple type:
  $make
And then under root:
  $make install
