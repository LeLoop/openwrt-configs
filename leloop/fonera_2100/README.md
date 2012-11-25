Hilight
=======

The firmware works out of the box on a fonera 2100. The ethernet port is the
gateway (IP retreived via DHCP) and the clients connect to the WLAN.
By default, the SSID is LeLoop and the password leloopxp.

TODO
====

Prior to any utilisation, you really should connect to the Fonera with telnet
and setup a root password (it will automatically disable telnet and enable SSH).
We use by default the channel 11 for no particular reason. Fell free to change it.

Building your own firmware
==========================

If you don't want to use the image provided in bin/, have a look here:
http://wiki.openwrt.org/doc/howto/build

And simply link files/ in your build root, the config files will be automatically
added.


