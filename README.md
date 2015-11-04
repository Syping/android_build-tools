Scripts and patches to build ROMs for Samsung Galaxy S II Plus (GT-I9105 and GT-I9105P)
==================================

How to get:
-------------
Run "git clone https://github.com/andixlm/android_build-tools_galaxys2plus-common build-tools" in root of ROM sources directory.

Description of scripts:
-------------
resync - reset all changes in ROM sources, sync and get prebuilts. Use "-o" to reset changes only.

patch - patch ROM sources.

build - build ROM. It asks for cleaning of out directory (make clean) and device (i9105 or i9105p), then build for chosen device. Also it handles 1st option ("i9105" or "i9105p" or "s2plus"). To build with cleaning use "-c" as a 2nd option. To build boot image (or recovery image) for device defined in 1st option w/o whole ROM building use 2nd option "-b" ("-r" for recovery).

Credits:
-------------
pawitp - patches
luk1337 - initial implementation of scripts
