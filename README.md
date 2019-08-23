# T460s-Clover
Clover Bootloader, Kexts, config and ACPI patches for ThinkPad T460s.
Based on tluck's repo: https://github.com/tluck/Lenovo-T460-Clover

## What's different from tluck's Clover config
- The touchpad driver was changed to acidanthera's VodooPS2 (https://github.com/acidanthera/VoodooPS2). This driver enables multitouch gestures on the Synaptic touchpad (but TrackPoint and top buttons do not work)
- Clover was updated to support macOS Catalina
- The other kexts were updated
- Every kext or patch associated with the DW1560 was removed (I plan on upgrading to a DW1820a)
- Legacy_Sierra_QMI was added to support the internal modem.

## What's working
Pretty much everything that's working with tluck's config, with the addition of multitouch, Force Touch (emulated) and the LTE Modem.

## What's not working
- SD Card reader
- TrackPoint + physical mouse buttons

## Testing
The config uploaded here was tested on a ThinkPad T460s with an i7-6600U CPU, Intel HD Graphics 520 GPU, 8GB RAM, 256GB NVMe Drive and a FHD Screen. If your config is different than mine, you may need to recompile the ACPI patches.

## Credit
Thanks to tluck for laying the groundwork for a working hackintosh on the T460s. I'd also like to thank RehabMan, Shmilee, vusun123, TimeWalker, Mieze and every other hacker who makes Hackintoshing possible.
