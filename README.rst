libpng for Android 
==================
This is a repackaging of libpng 1.6.15 for Android.

Most changes went in config.h and writing the Makefiles.

The original libpng website is : http://www.libpng.org/pub/png/libpng.html

Assuming 'ndk-build' is in your path, you can use the build.sh script to create a static library.

The 'master' branch of this repository contains upstream version 1.6.15. This
hasn't been tested much on Android.

The 'stable' branch of this repository contains the older 1.4.1 version which works fine on Android.
