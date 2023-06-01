librtmp and rtmpdump ready to compile for Windows
===========

This is the rtmpdump utility (and librtmp) VisualStudio project ready to compile for Windows.
The good thing is that OpenSSL and libz libraries and includes are already referenced and included in the project so you don't have to worry about that.
The includes are in the "include" folder, and the libraries are in the "libs" folder.

Credits
-------
The original project is taken from: [wujs](https://github.com/wujs/librtmp-and-rtmpdump-for-Windows)

How to setup
------------
Install Visual Studio 2022 then build it.

Test
------------
Test on win32 debug and release buildding.

Other things
------------
Debug folder is filled with a Windows 8 x64 compilation, just in case you directly need the libs.

