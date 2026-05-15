# rootAVD Usage Notes

## Fork

This is a fork of newBit's rootAVD : https://gitlab.com/newbit/rootAVD

## Changes

Updated local Magisk.zip with latest v30.7 APK from https://github.com/topjohnwu/Magisk/releases.


## Testing results:

Patched API 36 (Pixel 9 Pro) - successfully.
Patched API 37 (Pixel 9 Pro) - device very unstable after patching.

## Commands

```bash
rootAVD.bat system-images\android-37.0\google_apis_playstore_ps16k\x86_64\ramdisk.img FAKEBOOTIMG


   IN AVD (Magisk app should have launched):
      Select & Patch Image
         -> Downloads
           -> Select fakeboot.img
             -> Let's Go

After reboot:
    Open Magisk
       Select [Yes] when prompted to complete setup
```

