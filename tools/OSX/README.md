Software for Atari development on Mac OSX
=========================================
I recommend the following software for developing Atari 2600 games on Mac OSX.

1. TextMate version 1.5.11 (NOT version 2.0), http://macromates.com/
2. Stella, the Atari emulator, http://stella.sourceforge.net/downloads.php
3. The Atari 6502 plugin for TextMate from Ian Bogost. See the next section for detailed instructions.


Atari 6502 plugin by Ian Bogost
===============================

Originally available from http://www.bogost.com/blog/atari_vcs_programming_in_textm.shtml, but the installer
no longer works on many computers. This is an alternate distribution that allows manual
installation.

Installation steps
------------------
1. Install dasm
 1a. Copy dasm to /usr/bin
 1b. Make sure the permissions on the file are rwxr-xr-x (chmod 755)
2. Install the header files
 2a. Copy the vcs directory into /usr/include
 2b. Make sure the permissions on the vcs directory is rwxr-xr-x, and that the permissions on both header files is rw-r--r-- (chmod 644)
3. Add the TextMate Bundle
 3a. Double-click on the "Atari.tmbundle" file. TextMate should open and install it.

