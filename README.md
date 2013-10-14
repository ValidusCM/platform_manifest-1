TEAM Gummy
==============

Gummy AOSP 4.3

Sync and Build:
---------------

In terminal enter:

    {x}   repo init -u git://github.com/ValidusCM/platform_manifest-1.git -b jb4.3
    {x}   repo sync
    {x}   prebuilts/misc/linux-x86/ccache/ccache -M 50G
    {x}   . build/envsetup.sh && brunch "device" -j8

Devices Currently Supported:
----------------------------

This list is always subject to change:

