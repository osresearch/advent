![ADVENT under simh on a Mac](http://farm3.static.flickr.com/2919/14295396095_11539403fe.jpg)

ADVENT.FOR
====

Instructions for rebuilding ADVENT.SAV, ATEXT.DAT and AINDX.DAT from
the FORTRAN IV sources is posted at [trmm.net/advent](http://trmm.net/Advent)
A pre-built version of all of these is checked in so that you
can transfer them to your PDP-11 to run under RT-11 on your VT100.
The sources were downloaded from Rick Adam's detailed
[Colossal Cave sources page](http://rickadams.org/adventure/e_downloads.html).

If you don't have actual hardware1, you can run these with
[a simh emulated PDP-11](http://simh.trailing-edge.com/).

Also, I hear that DECUS is no longer responding to snail mail
to their address, even if you send it "Attention: Adventure
Maintenance".  The original message is still in the PDP-11
executable.

 Trammell Hudson
 hudson@trmm.net
 2014-05-29


Original README.1ST:
----

The material in RT11SRC is an uncorrected "ASCII Squirt" over a serial
line from our dear departed PDP 11/03 to a PC.  There are some stray
lines at the top and bottom of each file.  Also, the source code is
formatted via tabs, rather than spaces.

 Ken Plotkin
 kplotkin@access.digex.net
 October, 1994


Original README.DOC:
----

This directory contains all of DECUS 11-340, Adventure, copied to PC
files.  They are direct ASCII copies, and contain all characters from
the RT-11 version.  In particular, the sources contain tab characters,
and presume RT-11's interpretation of tabs.  Some editing/reformatting
will be necessary if you want to work from these.

Also, please note that this directory contains the original form of
ATEXT.TXT, within which the INFO text identifies DECUS for support.
Since DECUS obviously won't support the PC version (they don't even
know me), ATEXT.TXT and ATEXT.DAT on the rest of this disk have had
that removed.  Please don't mix up the text files.

When built under MSF 5.0, the magic wand (black rod) does not do its
thing when waved at the fissure.  Exact same code works just fine under
4.01.

This problem has driven me crazy.  Anybody who can figure out what's
wrong will receive a suitable reward:  Scott Adams's "Adventureland" and
"Pirate's Adventure" rewritten in Fortran IV for a DEC PDP 11/03.

