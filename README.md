# T460s-Clover (RehabMan PS2 Branch)
Clover Bootloader, Kexts, config and ACPI patches for ThinkPad T460s.
Based on tluck's repo: https://github.com/tluck/Lenovo-T460-Clover

***

This branch substitutes acidanthera's VoodooPS2 with RehabMan's version. Three finger swipes, Force Touch and others are not supported, but the TrackPoint and physical buttons are.

***

## What's different from tluck's Clover config
- Clover was updated to support macOS Catalina
- The other kexts were updated
- Every kext or patch associated with the DW1560 was removed
- Added support to the DW1820a Combo Card
- Legacy_Sierra_QMI was added to support the internal modem
- Added CPUFriend to bring base frequency down to 800MHz.
- Added the old Mac Boot chime (because it reminds me of my old iBook. and it's cute.)

## What's working
Pretty much everything that's working with tluck's config, with the addition of the LTE Modem.

## What's not working
- SD Card reader
- Multitouch (Botched implementation, 3 fingers not supported, etc.)

## Testing
The config uploaded here was tested on a ThinkPad T460s with an i7-6600U CPU, Intel HD Graphics 520 GPU, 8GB RAM, 256GB NVMe Drive and a FHD Screen. The Intel WiFi card was replaced with a DW1820a. If your config is different than mine, you may need to recompile the ACPI patches.

## Credit
Thanks to tluck for laying the groundwork for a working hackintosh on the T460s. I'd also like to thank RehabMan, Shmilee, vusun123, TimeWalker, Mieze and every other hacker who makes Hackintoshing possible.
