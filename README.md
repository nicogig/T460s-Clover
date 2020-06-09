# T460s-Clover
Clover Bootloader, Kexts, config and ACPI patches for ThinkPad T460s.
Based on tluck's repo: https://github.com/tluck/Lenovo-T460-Clover

## Switch to OpenCore

Please consider switching your current setup to OpenCore. I reccomend reinstalling macOS while switching, but you can definitely switch without wiping, as it has been done before. You can find my repo here: https://github.com/nicogig/Thinkpad-T460s-macOS-OpenCore

## This Repo is currently INACTIVE

Just a quick warning before you download and use my repo!
This repo is currently INACTIVE and hasn't been updated in a while (University work has definitely taken a toll on me this year!).

Thank you to everyone who downloaded, forked, and starred this repo. I hope you'll stick around for the OpenCore port!


## What's different from tluck's Clover config
- The touchpad driver was changed to acidanthera's VodooPS2 (https://github.com/acidanthera/VoodooPS2). This driver enables multitouch gestures on the Synaptic touchpad (but top buttons do not work)
- Clover was updated to support macOS Catalina
- The other kexts were updated
- Every kext or patch associated with the DW1560 was removed
- Added support to the DW1820a Combo Card
- Legacy_Sierra_QMI was added to support the internal modem
- Added CPUFriend to bring base frequency down to 800MHz.
- Added the old Mac Boot chime (because it reminds me of my old iBook. and it's cute.)

## What's working
Pretty much everything that's working with tluck's config, with the addition of multitouch, Force Touch (emulated) and the LTE Modem.

## What's not working
- SD Card reader
- Physical mouse buttons

## Testing
The config uploaded here was tested on a ThinkPad T460s with an i7-6600U CPU, Intel HD Graphics 520 GPU, 8GB RAM, 256GB NVMe Drive and a FHD Screen. The Intel WiFi card was replaced with a DW1820a. If your config is different than mine, you may need to recompile the ACPI patches.

## Credit
Thanks to tluck for laying the groundwork for a working hackintosh on the T460s. I'd also like to thank RehabMan, Shmilee, vusun123, TimeWalker, Mieze and every other hacker who makes Hackintoshing possible.
