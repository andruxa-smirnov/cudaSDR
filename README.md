This is a copy of VK5ABN, Berndt's cuSDR source
derived from his post: http://www.ping.net.au/20140126_cuSDR64src.tar.gz

This is originally cuSDR written by Hermann, DL3HVH
https://plus.google.com/107168125384405552048/posts

I added local sound and up'd the number of receivers to 20.

Using the Hermes-Lite (with some minor protocol changes)
I can do 16 rcvrs @ 96Khz and 9 @ 192Khz:
 https://cloud.githubusercontent.com/assets/944671/8505354/55e3d776-21b1-11e5-9607-f7abe94018fc.jpg

NOTES:

Greater than 7 rcvrs requires a protocol change which currently only
the Hermes-Lite rtl supports.

I have only compiled and used this on linux.

To make for Hermes-Lite edit Makefile and add -DHL
