# networkRefresh

dependencies:
	Perl
	networkManager

This program resets my network connection when a ping returns "Destination Host Unreachable"
I have been getting an odd error on my schools wifi and this is a temparary fix.

run this as ./networkRefresh "interface" to use a different interface. the default is "wlp1s0"


This creates some files wherever its run from. Make sure its started from the same place each time.
I start it with i3, so the files are located in my home dir.

This outputs to ".networkOutput". read this file for logs

This creates ".networkTimeStamp" to help determine when the machine stops. this updates every 5 minutes
You dont really need to look at this file

