Destiny WEM Converter
=====================

This is a tool optimised for bulk-converting Destiny WEM files into WAV format for use in audio projects.  

It is also possible to use it to convert WEM files from other games into WAV format.  

Please note that conversion will use a significant number of CPU cores and that converted files are very large.  

For the average Destiny 1 / 2 version, more than 90 GB of output will be produced.  

Wherever possible, it is usually better to convert to OGG files, which can be done losslessly using ww2ogg.

Building
--------

This program can be built using `ninja` at the top-level. It requires Ninja, GPRBuild, an Ada 2022 compiler,
a \*nix system (subject to change), and libvorbis. VGMStream, a required dependency, will be downloaded.
