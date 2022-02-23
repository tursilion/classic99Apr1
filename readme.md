20160401

Classic99 - a TI-99/4A Emulator for the TI-99/4A
------------------------------------------------

For a long time, people have asked me if I would port Classic99 to this system or that. Finally, I decided to start by porting to the system that I am most interested in, the TI-99/4A.

This is my first release. Compatibility is not bad, although there are a few restrictions:

1) It has only been tested with Editor/Assembler as the loader. Other loaders (including XB) will have varying results, probably poor.
2) It has been tested with the TI-99/4A v2 GROM and the v2.2 GROMs. It's not specifically tested with v1 GROMs but is expected to work.
3) It is NOT compatible with the TI-99/4 (no A)

Some known limitations:

-Only graphics 0 mode works! Sorry, no Parsec or Atarisoft in this release. No Funnelweb or F18A either. Sprites are fine though.
-Some programs are capable of escaping the sandbox and taking over the machine - be careful!
-The title bar may be corrupted by some programs -- this does not usually indicate a problem.
-Page flipping and smooth scroll usually will not work well
-There is 2k less video RAM available (mostly affects TI BASIC)
-Title bar may overwrite top line of some programs
-To exit you will need to power cycle your system.

So what can it do?

-TI BASIC works fully!
-Many EA#5 programs work fine (so long as they do not violate the above limitations)
-Some EA#3 programs work. Autostart is more likely to break than non-autostart.
-You no longer need to choose! Now you can run Classic99 in your choice of emulator -- MESS, JS99er, even Classic99!

Anyway, tested on Classic99 and MESS, and should work on iron. Enjoy!

