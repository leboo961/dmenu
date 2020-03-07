dmenu - dynamic menu
====================
dmenu is an efficient dynamic menu for X.

## Flag options

|Flag           | Action                                   |
|:-------------:|----------------------------------------|
| b             |shows dmenu at bottom on screen           |
| c             |shows dmenu centered on screen            |
| F             |disable fuzzy matching                    |
| fn            |override font use in dmenu                |
| i             |case insensitive search                   |
| l             |number of lines shown in the vertical list|
| n             |instant select only match                 |
| p             |add prompt to demnu                       |
| r             |output text each time key is pressed      |

Requirements
------------
In order to build dmenu you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install


Running dmenu
-------------
See the man page for details.
