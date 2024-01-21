# LTE_4G_WIFI_Dongle

How to reverse dongle:
1. Install https://github.com/bkerler/edl.git
2. Short two pins and connect usb (EDL mode) ![IMG_0120](https://github.com/cg10036/LTE_4G_WIFI_Dongle/assets/30382481/379d298f-dff5-416f-9d24-c77c73e03880)
4. Extract firmware with `edl rl dumps --genxml`
5. Mount system image with `sudo mkdir /mnt/system && sudo mount -o ro dumps/system.bin /mnt/system`
6. Extract `/mnt/system/priv-app/MifiService.apk`
