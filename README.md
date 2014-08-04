mmx_a110_device_tree
====================
copyto /something/cm11/device/micromax/a110

and setup vendor tree using ./extract-files.sh

and build commands are
 . build/envsetup.sh
 lunch cm_a110-userdebug
 make -j5 bacon
