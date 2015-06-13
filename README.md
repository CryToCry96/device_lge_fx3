Cyanogenmod 10 Device tree
=======================
**LG Optimus f3 - Virgin Mobile**
```
This is an attempt to create a cyanogenmod 10 device tree
for the LG Optimus F3 Virgin Mobile Phone.

http://androidforums.com/threads/rom-alpha-4-1-2-cyanogenmod-10-0-unofficial.879041/

This is a work in progress. At this stage the device tree is still a (wip) work in progress.
Device tree will not boot with out stock boot.img
```

Kernel I compile with is https://github.com/xclusive36/android_kernel_lge_fx3
***
IMPORTANT!!! Install into the ./kernel folder. Not ./kernel/lge/fx3 Otherwise build will fail.
Also, the boot.img will loki on install. To use the rom, you need to use the sprint/virgin mobile LS720ZV5 aboot.image
***

What works:
```
*Automatic brightness
*Calls
*Sms / Text message
*Sound
*Wifi
*Rotation
*Microphone
*Data/3G
*External SD
*Camera/Flash
*Speaker phone
*Wifi Hotspot <- See second post
*Home button LED Lights not 100%
*Headset/headphones
*GPS
*Accelerometer
``

What doesn't:
```
*Data-4g
*MTP
*Bluetooth
*Vibration
*???
```

```
I wanted to say thank you to cesarasm. Thank you :) You nuked your phone bringing this to our attention.
I also want to say thank you to phenomx4 for your kernel and device tree work. Your awesome :)
Thanks TrustME90 for the vold.fstab info
Thank you sandix for your bug testing and suggestions
Thank you masterdebugger for continuously digging and poking and getting GPS to work
Thank you Andresramirezvzla for figuring out the phone sound volume bug
```
