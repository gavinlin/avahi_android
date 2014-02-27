[http://avahi.org/ticket/354](http://avahi.org/ticket/354)

These patches enable building on Android. The first adds Android-specific and some workarounds where needed due to the Bionin libc library used by Android. The second one add uninstalled.pc.in files needed by Android's PKGCONFIG

To build on Android, you need Android NDK, and androgenizer, which is an open tool developed by Collabora to streamline generation of the Android.mk buildfiles from the Makefile.am (where Android.mk targets are added to help with it)
