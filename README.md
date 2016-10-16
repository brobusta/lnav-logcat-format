# lnav log format for Android logcat

[lnav](http://lnav.org) is an advanced log file viewer for the small-scale.
This repository contains file format descriptions for android logcat.

# lnav version

lnav version 0.8.1 or above.

# logcat format

logcat messages should be generated in **threadtime** output format:
> adb logcat -v threadtime
