# .config - A collection of my Buildroot config files
## What is buildroot?
See <a href="https://buildroot.org/">this</a>
## How to use this?
Clone this repo and copy the ****.config*** file you want and rename it to just ***.config***, then put it to the buildroot dir. After that you can import this ***.config*** file by using the command
``` bash
make oldconfig
```
Then you can use ```make menuconfig``` to edit the config to fit your setting or just ```make``` to build the image.
The default output is an ***.iso*** file at ```[YOUR_BUILDROOT_DIR]/output/images/rootfs.iso9660```
## What is this repo include?
|Name|Description|
|----|-----------|
|qemu.config|Buildroot with qemu-i386 only|
