Game_Music_Emu
==============

This is a fork of https://github.com/kode54/Game_Music_Emu. It attempts to fix
the platform-specific issues introduced in that fork, while keeping its
features.

The CMakeLists.txt configuration really needs some work to be "correct," but
it builds and runs right now if you don't tell it to omit any device support.

I've tested it with ffmpeg, where it works.

Original Kode54 README:

Game Music Emu - Multi-purpose console music emulator and player library

Note: I removed Data_Reader.h at some point in the past, so that the library
may be used in the same project as File_Extractor, which also has a repository
on my section of this site.

More documentation may or may not arrive soon.
